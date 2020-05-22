# Force Git Branch Plugin

Runs step on an alternative git branch.

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: ls
    plugins:
      - roverdotcom/force-git-branch#v1.0.0:
            branch: 'stable'
```

## Configuration

### `branch` (Required, string)

The git branch name, for example `master`–must already exist.
