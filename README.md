This repository contains my personal configuration for Visual Studio Code. Available here for my own ease of access and probably not useful for anyone else.

It's debatable whether anything in this repo is actually copyrightable. For clarity though, anything copyrightable to me in this repo is released under the Apache License, Version 2.0.

## Where to clone this?

* Windows: `C:\Users\USERNAME\AppData\Roaming\Code\User`
* macOS: `/Users/USERNAME/Library/Application Support/Code/User`
* Linux: `/home/USERNAME/.config/Code/User`

## Snippets

### C#

* *Optimized for loop* A for loop for iterating through a collection without calling `Count` on each iteration.
* *Iterate through listeners* A for loop to call a method on all listeners of a mtti.Inject service.
* *New MonoBehaviour* Boilerplate for a Unity MonoBehaviour class. Name derived from the file name.
* *Custom editor* Boilerplate for a custom Unity editor. Name derived from the file name.
* *Button* Unity inspector button.
* *Inject property* A property decorated with mtti.Inject.InjectAttribute.
* *Service* Boilerplate for a mtti.Inject service. Includes interfaces for the service and its listeners, methods for adding and removing listeners. Service name is derived from the file name.
* *ScriptableObject* A new Unity ScriptableObject class. Name derived from file name.

## Extensions

    $ code --list-extensions
    2gua.rainbow-brackets
    dbaeumer.vscode-eslint
    eamodio.gitlens
    eriklynd.json-tools
    ms-dotnettools.csharp
    ms-vscode.wordcount
    oderwat.indent-rainbow
    usernamehw.errorlens
