# Error Book

This file is the permanent record of mistakes, bugs, misunderstandings, and lessons learned.

## Format

### Date
### Topic
### Mistake
### Why It Happened
### Fix
### Lesson

## Example

### 2026-10-02
### Topic: Build pipeline
### Mistake: Assumed the compiler and linker were the same concept.
### Why It Happened: The build process was treated as a single opaque action.
### Fix: Break the build into compile, assemble, link, and run steps.
### Lesson: Understand each stage in the toolchain before optimizing or debugging.

---

Add entries as they happen. Errors are not failures; they are evidence of active learning.
