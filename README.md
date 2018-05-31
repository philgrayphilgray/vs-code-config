NOTE: A few hours after pushing this, I found a VS Code extension that has all the features I wanted and more for settings/extension syncing: (https://github.com/shanalikhan/code-settings-sync)[https://github.com/shanalikhan/code-settings-sync].


# VS Code Config and Extensions

A central repo for the VS Code config and extensions I use on my primary machine.

These shell scripts are peculiar to my MacOS machines.

To take a snapshot of the current extensions/config:

```bash
npm run snapshot
```

To overwrite the current user config and install all the extensions from the snapshot:

```bash
npm run install
```

* TODO: Use relative OS paths.
* TODO: Filter for only `@enabled` extensions, disable all extensions before install, and re-enable upon install.
