# Middleware Directory

This directory contains Express middleware used throughout the application.

## Common Middleware

- `auth.js` - Authentication middleware
- `errorHandler.js` - Global error handling
- `requestLogger.js` - Request logging
- `validation.js` - Request validation helpers

## Best Practices

1. Each middleware should focus on a single responsibility
2. Handle errors properly
3. Be mindful of middleware order
4. Document middleware purpose and behavior