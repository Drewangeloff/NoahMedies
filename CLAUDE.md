# CLAUDE.md - Guidelines for AI Coding Agents

## Build & Test Commands
- Build: `npm run build`
- Lint: `npm run lint`
- Type check: `npm run typecheck`
- Test (all): `npm test`
- Test (single): `npm test -- -t "test name"`
- Run dev server: `npm run dev`

## Code Style Guidelines
- **Formatting**: Follow Prettier defaults, 2-space indent
- **Imports**: Group by type (React, libraries, internal), sort alphabetically
- **Naming**: camelCase for variables/functions, PascalCase for classes/components
- **Types**: Use TypeScript, prefer explicit return types, avoid `any`
- **Components**: Functional components with React hooks
- **Error Handling**: Use try/catch for async operations, proper error propagation
- **State Management**: Follow immutability principles, avoid direct mutations
- **Comments**: JSDoc for public API, implementation notes for complex logic
- **Testing**: Unit tests for logic, integration tests for workflows

_Update this file as the project evolves with more specific standards._