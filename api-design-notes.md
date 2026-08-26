# API Design Notes

Collected during today's lunch break.

- Use consistent resource naming: plural nouns, not verbs.
- Prefer nested routes only for obvious hierarchies.
- Return stable IDs and include `type` in JSON payloads.
- Document errors with `code`, `message`, and `details`.
- Version via URL path (`/v1`) for now, not headers.
