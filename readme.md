# Emoji Commit on NPM

The is the NPM release of [the emoji committer](https://github.com/LinusU/emoji-commit) 🎉

## Installation

```sh
npm install -g emoji-commit
```

## Usage

The emoji committer can be used in two ways. Either invoked directly, or by configuring git to invoke it.

### Invoke directly

Simply call `emoji-commit` as you would any other command:

```sh
emoji-commit
```

### Configure Git

You can set the `core.editor` configuration in git the the emoji committer to always use it when committing.

```sh
git config --global core.editor 'emoji-commit'
```
