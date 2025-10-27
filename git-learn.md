## Git

- Everything in GIT is an object just like JavaScript.

# 3 Muskeeters of Git

## Commit Object

- Each commit is stored in .git folder in the form of commits and contains the following information
  1. Tree Object
  2. Parent Commit Object
  3. Author
  4. Committer
  5. Commit Message

## Tree Object

- Everything is stored in key-value pair
- A container for all the files and folders in the project.

  1. File Mode
  2. File Name
  3. File Hash
  4. Parent Tree Object

## Blob Object

- Blob is present in the tree object and contains the actual file content where the file content is stored.
