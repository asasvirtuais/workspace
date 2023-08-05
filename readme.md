Asas Virtuais in an Open Source initiative for Web Development

This repository is a pnpm workspace that allows developers to share local dependencies across multiple projects. Local dependencies are installed from the packages directory instead of being downloaded from the npm Registry.

[PNPM](https://pnpm.io/workspaces) is recommended here because, as of the time this was written, it is the best and fastest package manager for TypeScript.

[TypeScript](https://www.typescriptlang.org/) is required, to simplify the development process Asas Virtuais packages are not transpiled to JavaScript.

[Caddy](https://caddyserver.com/) is recommended for development to allow https on localhost with ease.


**Usage**

To use this repository you have to create the "packages" directory and clone the repositories you want to contribute to in there, it is not included in the repository because I believe it is important for contributors to understand they are doing, by creating the directory themselves contributors show that they are qualified to make contributions.
