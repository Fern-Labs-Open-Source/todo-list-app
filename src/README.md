# Source Code Directory

This directory contains all the source code for the Todo List application.

## Directory Structure

Following the structure defined in our [Development Guide](../development.md):

### Frontend Structure
```
/assets         # Static files like images, fonts
/components     # Reusable UI components
  /common       # Generic components (Button, Input, etc.)
  /layout       # Layout-related components
  /features     # Feature-specific components
/hooks          # Custom React hooks
/pages          # Page components
/routes         # Routing configuration
/services       # API communication and other services
/store          # State management (Redux)
  /slices       # Redux slices for features
  /middleware   # Redux middleware
/styles         # Global styles and themes
/types          # TypeScript type definitions
/utils          # Utility functions
/tests          # Test files (can also be co-located with components)
```

### Backend Structure
```
/api            # API routes and controllers
  /v1           # API version 1
/config         # Configuration files
/middleware     # Express middleware
/models         # Database models
/services       # Business logic services
/utils          # Utility functions
/validation     # Input validation schemas
/tests          # Test files
```

Following our quality-focused development approach, each component or module should be:

1. Well-documented with appropriate comments
2. Include test files covering critical functionality
3. Follow the established coding standards
4. Maintain single responsibility principle