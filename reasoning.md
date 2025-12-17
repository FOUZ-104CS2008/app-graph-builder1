## Approach
I built the App Graph Builder using React + Vite with TypeScript.
ReactFlow (xyflow) is used to render the canvas and manage nodes.
Zustand is used for global state such as selected node.
TanStack Query is used for fetching mock API data.
shadcn/ui is used for building consistent UI components.

## Key Decisions
- Used Zustand for simple and predictable state management.
- Used ReactFlowProvider to enable canvas interactions.
- Kept the layout modular (top bar, left panel, canvas, right inspector).

## Trade-offs
- Used mock APIs instead of a real backend.
- Focused on clarity and correctness over extra features.
