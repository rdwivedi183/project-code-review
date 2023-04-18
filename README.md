# Point should be verify in Project.

- Make sure your code is clean.
- Debugging consoles should be removed.
- Put the name of the project you worked on in the commit.
- The commit must be spelled correctly.
- Make sure there are no duplicate codes.
- Develop a reducing code.
- The code should be reusable. Never rewrite the same code with the same functionality twice.
- Make .README.md file with proper documentation for local development and server.
- Must make the .README and .gitignore files.
- Mentioned the storage folder name in gitignore.
- Create a variable with the meaningful name.
- Remove all warning error from browsers console.
- Remove all variables and dependencies which is not used.
- Make sure your .env file should add in .gitignore.
- Remove all commented code.

# Commit should be like this - 
    **Semantic Commit Messages:**
  - feat (new feature for the user, not a new feature for build script)
  - fix (bug fix for the user, not a fix to a build script)
  - docs (changes to the documentation)
  - style (formatting, missing semi colons, etc; no production code change)
  - refactor (refactoring production code, eg. renaming a variable)
  - test (adding missing tests, refactoring tests; no production code change)
  - chore (updating grunt tasks etc; no production code change)

**Format of the commit message:**
```
<type>(<scope>): <subject>

<body>

<footer>
```
**Example commit message:**
```
fix(middleware): ensure Range headers adhere more closely to RFC 2616

Add one new dependency, use `range-parser` (Express dependency) to compute
range. It is more well-tested in the wild.
```

