# VS Code Config and Extensions

A central repo for the VS Code config and extensions I use on my primary machine.

To update:

```bash
npm run update
```

This will execute the following bash command:

```bash
code --list-extensions | xargs -L 1 echo code --install-extension  > extensions.txt && cp  ~/Library/Application\ Support/Code/User/settings.json ./
```

TODO: Use relative OS paths.
TODO: Add an install script for quick syncing other machines.
