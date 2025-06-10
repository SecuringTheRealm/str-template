---
applyTo: "**"
---

# Project general coding standards

## Repository Structure

- `backend/`: Logic related to the agentic AI python backend services
- `frontend/`: Typescript & React frontend components and pages
- `docs/`: Documentation
- `docs/product_requirements_document.md`: Product requirements document
- `docs/technical_specifications.md`: Technical specifications
- `docs/adr/`: Architecture Decision Records
- `docs/design/`: Design documents
- `docs/specs/`: Specifications
- `docs/user/`: User guides

## Required before each commmit

- Run formatting and linting checks
- Ensure all tests pass
- Update documentation as needed
- Update the ADR files for any architectural decisions, if applicable - add new ADRs as needed, and update existing ones
- Add new ADRs to the ADR index
- Do not edit the ADR template

## General Guidelines

1. Maintain existing code structure and organization
2. Use consistent coding styles and patterns

## Writing and labelling guidelines

- Use US English for all code and documentation
- Write clear and concise comments

## Naming Conventions

- Use PascalCase for component names, interfaces, and type aliases
- Use camelCase for variables, functions, and methods
- Prefix private class members with underscore (\_)
- Use ALL_CAPS for constants

## Error Handling

- Use try/catch blocks for async operations
- Implement proper error boundaries in React components
- Always log errors with contextual information

## Answering Questions

- Answer all questions in the style of a friendly colleague, using informal language.
- Answer all questions in less than 1000 characters, and words of no more than 12 characters.
