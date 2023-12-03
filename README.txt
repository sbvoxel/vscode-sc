// TODO: This file gets included into the package automatically
// and displayed in vscode's extension view.
// So we should have a parent directory that includes this.

// TODO: I'm not noticing the Golang people point to a language-configuration.json

// Because Golang people have put effort into their stuff, presumably, we'll copy
// them. They don't have a grammar for their base language, only for special files.
// This indicates they are relying on LSP server. So we'll do that. (TODO)

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

