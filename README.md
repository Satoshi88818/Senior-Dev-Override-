#Senior Dev Override with Grok.


[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue.svg)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> Production-grade codebase maintained with the **Senior Dev Override** philosophy.

## Development Philosophy

This project follows a strict **Senior Dev Override** workflow when working with Grok (or any AI coding assistant).

Instead of accepting "good enough" or junior-level code, every change must meet the standards of a senior software engineer with 15+ years of experience shipping large-scale systems.

The guiding principle is simple:

> **"What would a senior, perfectionist developer reject in code review?"**

All visible technical debt is fixed when files are touched. Cleanliness, correctness, maintainability, and long-term health take priority over speed.

## Senior Dev Override Setup

### 1. Grok Configuration File

The project includes a powerful configuration file:

- **`GROK.md`** – Senior Dev Override directives

This file is automatically referenced at the start of coding sessions with Grok.

### 2. How to Activate the Senior Dev Override

When starting a new coding session with Grok, begin with one of these commands:

```text
Apply the Senior Dev Override from GROK.md
```

Or simply:

```text
Load GROK.md and apply Senior Dev Override for all work
```

For best results, occasionally remind Grok during long sessions:

```text
Remember to follow the Senior Dev Override from GROK.md
```

### 3. What to Expect

When the Senior Dev Override is active, Grok will:

- Ruthlessly clean up dead code, unused imports, console logs, and commented code **before** making changes (Step 0 Rule)
- Break large refactors into small, safe phases (max ~4-6 files per phase)
- Always verify changes with type checking, linting, **and** relevant tests before declaring success
- Re-read files before and after edits to prevent context loss or incorrect changes
- Fix visible technical debt and inconsistencies opportunistically while staying on task
- Think and act like a principal-level engineer who will own this codebase for years

### 4. Verification Commands (Always Run)

Before any change is considered complete, Grok must confirm:

```bash
npx tsc --noEmit          # Type checking
npx eslint . --quiet      # Linting
npm test -- path/to/changed/files   # Relevant tests
```

Only after these pass cleanly will a task be marked as complete.

## Project Structure

```
├── GROK.md                 # Senior Dev Override configuration (critical)
├── README.md               # This file
├── src/
├── tests/
├── package.json
└── ...
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start development with Grok using the Senior Dev Override (see instructions above)

## Contributing

All contributions (whether human or AI-assisted) must follow the Senior Dev Override principles.

- Changes must be clean, well-structured, and review-ready
- Technical debt must be addressed when files are touched
- Every PR should pass full type checking, linting, and tests

## License

MIT 

---

**Maintained with pride using the Senior Dev Override.**
```



