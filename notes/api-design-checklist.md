# API Design Checklist

Some quick reminders for future playground experiments.

- Use consistent resource names and HTTP verbs.
- Return meaningful error codes and messages.
- Version from day one, even if it feels early.
- Document the happy path and the failure cases.
- Keep JSON responses flat unless nesting adds clarity.
- Prefer small, focused endpoints over one big blob.
- Add pagination before consumers ask for it.
- Think about idempotency for POST/PATCH where it matters.

More notes will land here as I explore new ideas.