# Welcome to your VS Code Extension Pack

## What's in the folder

* This folder contains all of the files necessary for your extension pack.
* `package.json` - this is the manifest file that defines the list of extensions of the extension pack.

## Making changes
Add/remove extensions in the `package.json` and then update the documentation in both `CHANGELOG.md` and `README.md`.

Run the following command to generate the extension file:
`vsce package`

### Publishing changes
After merging any changes into the GH repo, sign into the VS Code Marketplace, click "Publish Extensions." From the extension list, choose "Update" on this extension and upload the new VSIX file.
