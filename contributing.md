# Contributing to Aluminium
First of all, thank you for considering contributing to Aluminium!
Everyone is welcome to contribute, whether you're fixing a bug, optimizing performance, or improving documentation.

## Philosophy
Aluminium is **not** designed to be a generic file transfer and compression utility. Its main purpose is to **compress archives and backups** in an efficient and customizable way.

That said, while performance optimizations (CPU, RAM usage, Fast compression, etc.) are not the top priority, such contributions are always appreciated — as long as they do not compromise code clarity or maintainability.

## Contribution Guidelines
To keep the codebase clean, idiomatic, and maintainable, please follow these guidelines:

1. 🦀 Use idiomatic Rust
- Favor expressive, safe, and idiomatic Rust patterns.
- Use Result and proper error handling instead of panics.
- Prefer Option and iterators over manual loops and control flags.

2. 📚 Document your code
- Use ``///`` doc comments for all public items (functions, structs, modules).
- If your feature changes behavior, update the ``readme.md`` or relevant docs.
- Write inline comments for non-obvious logic.

3. 📦 Dependencies
- Only add a new crate if necessary.
- Prefer lightweight, well-maintained crates.
- If adding a dependency, explain why in the PR or issue.

4. 🧪 Tests and correctness
- Add unit tests for new logic.
- If it’s a fix, add a test to prevent regression.
- Run tests with cargo test before submitting a PR.

5. 💄 Code formatting and linting
- Run cargo fmt to auto-format your code.
- Run cargo clippy and fix warnings if possible.
- Keep the code clean and readable.

6. 🧵 Commit structure
- Use meaningful commit messages:
    fix: correct buffer size in compressor
    feat: add multithreaded archive creation
- Squash small fix-up commits if possible.

7. 🧠 Open an issue before big changes
- For large features or refactors, open an issue to discuss your plan before starting.
- This avoids duplicated work and helps ensure alignment with project goals.

8. 🤝 Respect and collaboration
- Be respectful in code reviews and discussions.
- Help others if you can.
-  We value clean, maintainable, and thoughtful contributions.