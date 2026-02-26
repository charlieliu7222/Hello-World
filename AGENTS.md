# AGENTS.md

## Cursor Cloud specific instructions

This is a minimal C repository containing a single source file (`HelloWord.c`).

### Build & Run

```bash
gcc HelloWord.c -o hello && ./hello
```

GCC (Ubuntu 13.x) is pre-installed in the VM. No external dependencies, package managers, build systems, or services are required.

### Notes

- There are no tests, linters, or CI pipelines configured in this repository.
- The compiled binary (`hello`) is a build artifact and should not be committed.
