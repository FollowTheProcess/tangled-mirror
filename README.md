# Tangled Mirror

A GitHub action to mirror a repository to [tangled.org]

<!-- action-docs-all source="action.yml" project="FollowTheProcess/tangled-mirror" version="v1" -->
## Description

GitHub Action to mirror the current repository to tangled.org

## Inputs

| name | description | required | default |
| --- | --- | --- | --- |
| `tangled-ssh-key` | <p>The private SSH key for tangled.org (use a GitHub secret!)</p> | `true` | `""` |
| `tangled-handle` | <p>Your tangled.org handle e.g. yourname.tngl.sh</p> | `true` | `""` |


## Runs

This action is a `composite` action.

## Usage

```yaml
- uses: FollowTheProcess/tangled-mirror@v1
  with:
    tangled-ssh-key:
    # The private SSH key for tangled.org (use a GitHub secret!)
    #
    # Required: true
    # Default: ""

    tangled-handle:
    # Your tangled.org handle e.g. yourname.tngl.sh
    #
    # Required: true
    # Default: ""
```
<!-- action-docs-all source="action.yml" project="FollowTheProcess/tangled-mirror" version="v1" -->

[tangled.org]: https://tangled.org
