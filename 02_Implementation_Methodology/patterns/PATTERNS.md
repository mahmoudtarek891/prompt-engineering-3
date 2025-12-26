# Design Patterns

## SWM (Standard Wave Module) Pattern
Each module follows a consistent structure:
- `types.ts` - Type definitions
- `store.ts` - State management
- `api.ts` - External communication
- `utils.ts` - Helper functions
- `index.ts` - Public exports

## Contract-First Pattern
1. Define interfaces before implementation
2. Document expected behavior
3. Implement against contract
4. Verify compliance

## TPN (Task Priority Number) Pattern
Priority = (Impact × Urgency) / Complexity
- Impact: 1-10
- Urgency: 1-10
- Complexity: 1-10
