# Contributing

This is a personal reading list, so I don't accept pull requests.

## Suggestions

If you have a recommendation, spot a dead link, or think something belongs in a different section, feel free to [open an issue](../../issues/new). Please include:

- The link
- Why you think it's worth reading (one sentence is fine)

I'll read everything suggested before adding it, and the comment on each entry is written by me. If I add your suggestion, I'll credit you next to the entry with "(via @username)".

## Commit Messages

Commits follow this format:

```
<type>(<section>): <subject>
```

### Types

| Type      | Use for                                            |
|-----------|----------------------------------------------------|
| `add`     | Adding an entry                                    |
| `update`  | Changing an entry's comment, title, or URL         |
| `remove`  | Removing an entry                                  |
| `move`    | Moving an entry to another section                 |
| `fix`     | Fixing a dead link or typo                         |
| `section` | Adding, renaming, or removing a section            |
| `chore`   | Anything else (README intro, license, this file)   |

### Sections

Use the section name in lowercase kebab-case, e.g. `software-engineering`. Omit the scope for changes that aren't tied to one section.

### Subject

- Imperative mood, lowercase, no trailing period
- Wrap entry titles in double quotes

### Examples

```
add(software-engineering): "How to Avoid Merge Conflicts"
update(essays): rewrite comment for "..."
remove(industry-and-trends): "..."
move(industry-and-trends): "..." from software-engineering
fix(working-effectively): replace dead link to todo.txt spec
section: add/remove industry-and-trends
chore: update README intro
```
