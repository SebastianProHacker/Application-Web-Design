# Application Web Design

## Personal Data
- **Name:** Sebastián Navarro Cavazos
- **Registration Number:** 2912926
- **Degree:** Software Development Engineering
- **Semester:** 6th

## Subject Information
- **Subject:** Application Web Design
- **Professor:** Mario Eduardo Rodríguez Palafox

## What is Markdown?
Markdown is a lightweight markup language used to format text in a simple and readable way. It is commonly used for documentation, readme files, and writing content for the web. Its syntax is easy to learn and allows you to create headings, lists, links, and much more.

## Markdown Tagging Options

### Headings
Use `#` for headings:
- `# Heading 1`
- `## Heading 2`
- `### Heading 3`

### Text Formatting
- **Bold:** `**text**`
- *Italic:* `*text*`
- ~~Strikethrough:~~ `~~text~~`

### Lists
- **Unordered lists:**  
  Use `-`, `+`, or `*`:
  ```
  - Item 1
  - Item 2
  ```

- **Ordered lists:**  
  Use numbers followed by a period:  
  ```
  1. Item 1
  2. Item 2
  ```

### Links
Create hyperlinks using `[text](URL)`:
```
[Visit GitHub](https://github.com)
```

### Images
Embed images with `![alt text](URL)`:
```
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

### Code
- **Inline code:** Use backticks: `` `code` ``
- **Code block:** Use triple backticks (```) or indent with four spaces:
  ```bash
  echo "Hello, world!"
  ```

### Tables
Create tables using pipes (`|`) and dashes (`-`):
```
| Column 1 | Column 2 |
|----------|----------|
| Data 1   | Data 2   |
```

### Blockquotes
Use `>` for blockquotes:
```
> This is a blockquote.
```

---

## Git Commands Reference

### Check the status of a local repository
To see the current state of your working directory:
```bash
git status
```

### Add files to the staging area
To add individual files:
```bash
git add <file_name>
```
To add all changes:
```bash
git add .
```

### Create commits
To commit changes with a descriptive message:
```bash
git commit -m "Your commit message here"
```

### Push changes to the remote repository
To upload your changes to GitHub:
```bash
git push origin main
```

### Branch management
- **Create a new branch:**
  ```bash
  git branch <branch_name>
  ```
- **Browse a branch:**
  ```bash
  git branch | grep feature
  ```
- **Switch to another branch:**
  ```bash
  git checkout <branch_name>
  ```
- **Delete a branch:**
  ```bash
  git branch -d <branch_name>
  ```

### Roll back to a specific commit
To revert the repository to a specific commit (be careful with this command):
```bash
git reset --hard <commit_hash>
```



