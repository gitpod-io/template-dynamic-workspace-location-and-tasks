# Dynamic workspace root

Dynamically change VSCode [workspaceLocation](https://www.gitpod.io/docs/references/gitpod-yml#workspacelocation) based on context.

Browse to one of the subdirectories on this repo and open a workspace from there. Or you can also click on a button below!

- [![docs](https://shields.io/badge/style-docs-green?logo=gitpod&style=for-the-badge&label=Gitpod)](https://gitpod.io/#https://github.com/gitpod-io/template-dynamic-workspace-location/tree/main/docs)
- [![examples](https://shields.io/badge/style-examples-green?logo=gitpod&style=for-the-badge&label=Gitpod)](https://gitpod.io/#https://github.com/gitpod-io/template-dynamic-workspace-location/tree/main/examples)
- [![practice](https://shields.io/badge/style-practice-green?logo=gitpod&style=for-the-badge&label=Gitpod)](https://gitpod.io/#https://github.com/gitpod-io/template-dynamic-workspace-location/tree/main/practice)

# Details

A [.gitpod.yml](./.gitpod.yml) task is used to process `$GITPOD_WORKSPACE_CONTEXT_URL` variable. Later `code -r` command is used if a subdirectory was found on the CONTEXT_URL.
