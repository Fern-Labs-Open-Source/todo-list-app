# Pages Directory

This directory contains components that represent entire pages in the application.

Each page should:
1. Be primarily composed of components from the components directory
2. Handle page-level state and data fetching
3. Connect to the global state if needed
4. Be responsible for layout of the page components

Pages should not contain a lot of direct UI implementation, but rather compose UI from existing components.