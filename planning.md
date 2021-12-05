# planning

## cli
commands:
- bookgen init
    1. runs `git init`
    2. queries info like title, author(s), etc.
    3. creates src/first-chapter.md
    4. creates bookgen.toml with provided info & dummy first chapter
- bookgen gen chapter "Chapter Name" path/to/chapter.md
- bookgen build - builds the book, and outputs to the target/ directory

## gitpodifying
