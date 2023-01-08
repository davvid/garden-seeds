# Garden Soil

Soil helps gardens grow.

This is my personal colleciton of reusable templates for
[Garden](https://github.com/davvid/garden).

Garden is a developer tool for working with collections of Git worktrees.


## Usage

Add this snippet to your `garden.yaml`:

```yaml
garden:
    includes: garden-soil/templates.yaml
trees:
    garden-soil: https://github.com/davvid/garden-soil.git
```

And then run:

```bash
garden grow garden-soil
```

The templates, variables and commands are now available in your `garden.yaml`.