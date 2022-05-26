# Because libraries are sometimes big and cumbersome

This project aims to be a template for my own vanilla website projects.

It might not be maintained so don't plainly copy it. Use it for inspiration if needed.

## Folders

- `/scripts` - esbuild scripts used to spin up dev server, compile the ts and build the final site
- `/src` - source .ts and .css files
- `/src/routes` - These files will be used as entrypoints for the esbuild
- `/src/components` - Here I have included a example of the way I like to make vanilla js components with Web-Components
- `/public` - All the HTML entrypoints (and compiled .js and .css files)

## Features

- Auto building dev server
- Build time code bundling, tree shaking, minification and bundle splitting
- 0 kb dependencies on the client side
