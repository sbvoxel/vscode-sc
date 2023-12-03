// TODO: This file gets included into the package automatically
// and displayed in vscode's extension view.
// So we should have a parent directory that includes this.

First steps:

    npm install -g @vscode/vsce

    vsce package

Note that the second command will warn of a few things because
the current package is only suitable for local usage.

Now, to install locally from this package:
    open vscode
    go to extensions tab
    click '...'
    click 'Install from VSIX...'
    Navigate to, and select the file produced by the vsce command

You're done.

