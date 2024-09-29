1. Setup the project
   - Run using docker
   ```bash
   docker-compose up
   docker compose exec directus npx directus schema snapshot /directus/snapshots/snapshot.yaml
   ```
   - Without docker
   ```bash
   npm install
   npm run bootstrap
   npm run snapshot-apply
   npm run start
   ```
2. Environment configuration
   - Copy the `.env.example` to a new file named `.env` and adjust as needed.
   ```bash
   cp .env.example .env
   ```

3. Running the application
   - Directus Admin Dashboard: `http://localhost:8055`
