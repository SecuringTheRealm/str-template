---
applyTo: "**/*.ts,**/*.tsx"
---

# Project coding standards for TypeScript and React

Apply the [general coding guidelines](./general-coding.instructions.md) to all code.

## TypeScript Guidelines

- Use TypeScript for all new code
- Follow functional programming principles where possible
- Use interfaces for data structures and type definitions
- Prefer immutable data (const, readonly)
- Use optional chaining (?.) and nullish coalescing (??) operators

## React Guidelines

- Use functional components with hooks
- Follow the React hooks rules (no conditional hooks)
- Use React.FC type for components with children
- Keep components small and focused
- Use CSS modules for component styling
- Develop reusable components when possible

## Linting and Formatting

- Use Biome for linting and formatting
- Ensure all linting and formatting rules pass before submitting code

## UI Theming Guidelines

### General Practices

- Use CSS variables for consistent and flexible theming across all components.
- Ensure responsiveness across all UI components to support various screen sizes and devices.

### Colour Usage in UI Components

- **Titles & Headlines**:

  - highlight titles, section headers, and primary call-to-action buttons.
  - Maintain consistent usage for visual hierarchy.

- **Backgrounds & Containers**:

  - Employ lighter shades of gray for backgrounds to provide clean, neutral spaces that enhance readability and contrast.
  - Utilize medium to dark shades of gray for subtle delineations, borders, or UI separators.

- **Interactive & Highlight Elements**:
  - Buttons, links, and interactive highlights should consistently use the same color to reinforce brand identity and clearly indicate actionable items.
