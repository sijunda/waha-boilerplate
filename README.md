# Waha Project

A web application project with session management and media handling capabilities.

## Project Structure

- `.env-example` - Example environment variables file
- `.gitignore` - Git ignore configuration
- `docker-compose.yaml` - Docker configuration for containerized deployment
- `media/` - Directory for media assets with its own README
- `sessions/` - Directory for session data with its own README

## Features

- Session management system stored in SQLite database
- Media file handling and organization
- Docker containerization support
- Environment configuration management

## Setup

1. Copy `.env-example` to `.env` and configure your environment variables
2. Install dependencies if any (check for package.json, requirements.txt, etc.)
3. Use Docker Compose to run the application:
   ```bash
   docker-compose up
   ```

## Directories

- `media/` - Contains media assets for the application
- `sessions/` - Contains session data, including SQLite database files in `noweb/default/`

## Configuration

The project uses environment variables for configuration. Check the `.env-example` file for required variables.

## Docker Support

The project includes a `docker-compose.yaml` file for easy containerized deployment and development.

## Security Note

The `sessions/` directory contains sensitive session data. Ensure proper access controls are in place when deploying to production.