# mcp-servers

This repository provides configuration files for managing and launching multiple MCP servers using Docker Compose.

## Files

- `compose.yaml`: Service definitions for Docker Compose
- `.env`: Environment variables for services (tokens, URLs, etc.)

## Usage

1. Create a `.env` file and set the required environment variables.
2. Start the services with:

   ```sh
   docker compose up -d
   ```

## License

MIT License
