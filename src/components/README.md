# Components Directory

This directory contains all reusable UI components for the Todo List application.

## Structure

- `/common` - Generic UI components (Button, Input, Modal, etc.)
- `/layout` - Layout components (Header, Footer, Sidebar, etc.)
- `/features` - Feature-specific components organized by feature

## Best Practices

1. Each component should be in its own directory with the following structure:
   ```
   /ComponentName
     - index.tsx        # Main component file
     - ComponentName.tsx  # Component implementation
     - ComponentName.test.tsx  # Component tests
     - ComponentName.styles.ts  # Styled components (if using styled-components)
     - types.ts         # TypeScript interfaces/types (if needed)
   ```

2. Components should be focused on a single responsibility
3. Prefer functional components with hooks over class components
4. Follow the established naming conventions
5. Add appropriate PropTypes or TypeScript interfaces