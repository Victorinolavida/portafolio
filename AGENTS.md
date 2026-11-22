# Branch workflow

- Never push directly to `main` or merge a feature branch directly into `main`. Changes must first be merged into `dev`.
- Promote changes to `main` by merging `dev` into `main`, using a pull request.
- Merge feature and other working branches into `dev` using a pull request. After the merge, delete the merged working branch locally and remotely when it exists.
- Never delete the `main` or `dev` branches, locally or remotely.
