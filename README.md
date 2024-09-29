1. Setup the project
   - Run using docker
   ```bash
   docker-compose up
   docker exec -it directus npx directus schema apply ./snapshots/snapshot.yaml
   ```
2. Environment configuration
   - Copy the `.env.example` to a new file named `.env` and adjust as needed.
   ```bash
   cp .env.example .env
   ```

3. Running the application
   - Directus Admin Dashboard: `http://localhost:8055`
