# Custom Skills

This file defines custom skills for Claude Code in this project.

## Example Skill: Hugo Server

```yaml
name: hugo-serve
description: Start the Hugo development server
command: hugo server -D
```

## Example Skill: Hugo Build

```yaml
name: hugo-build
description: Build the Hugo site for production
command: hugo --minify
```

## Example Skill: New Post

```yaml
name: new-post
description: Create a new blog post with Hugo
command: hugo new content/post/{{year}}/{{title}}.md
args:
  - name: year
    description: Year for the post (e.g., 2024)
    required: true
  - name: title
    description: Title of the post
    required: true
```

---

## How to Use

Define skills using YAML blocks with the following structure:

- **name**: Unique identifier for the skill (used when invoking)
- **description**: What the skill does
- **command**: The shell command to execute
- **args** (optional): Arguments that can be passed to the skill

Invoke skills using: `/skill-name` or by asking Claude to run them.
