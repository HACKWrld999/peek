## Installing git-peek

You'll need to have [`git-peek`](https://github.com/jarred-sumner/git-peek) installed for this to work and only Windwos & macOS are supported for now.

To do that, run this:

```bash
npm install -g @jarred/git-peek
```

Next, you'll need to register the `git-peek://` URL handler. Just run this:

```bash
git peek -r
```

Then, head over to the test page:

<a href="https://github.com/Jarred-Sumner/1-click-from-github-to-editor/blob/main/TEST-PAGE.md">
  <img src="./test-button-img.png" height="48" />
</a>

### Private repoistories

To use Peek with a private repository, set your `$GITHUB_TOKEN` in `~/.git-peek`:

```
GITHUB_TOKEN="*******"
EDITOR="code" # optional
```

Read more on the docs for [`git-peek`](https://github.com/jarred-sumner/git-peek).
