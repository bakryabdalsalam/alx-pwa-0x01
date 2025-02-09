## API Overview
The MoviesDatabase API provides comprehensive movie data including titles, release years, images, and genre information. It offers endpoints for searching and filtering movies by various criteria.

## Version
Current API version: 1.0

## Available Endpoints
- `/titles`: Get movie titles with filters
- `/genres`: List available genres
- `/images`: Access movie poster images
- `/releases`: Get release information

## Request and Response Format
**Example Request:**
```http
GET /titles?year=2020&genre=Action