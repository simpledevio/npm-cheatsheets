# npm Cheat Sheet

## package.json

Create package.json:

`npm init`

Create package.json and skip questions:

`npm init -y`

## Local Packages

Install dependency:

`npm install <package_name>`

Install devDependency:

`npm install <package_name> --save-dev`

Run:

`npx <package_name>`

Update all packages:

`npm outdated`

`npm update`

Update single package:

`npm outdated`

`npm update <package_name>`

Uninstall dependency:

`npm uninstall <package_name>`

Uninstall devDependency:

`npm uninstall <package_name> --save-dev`

## Global Packages

Install:

`npm install -g <package_name>`

Update all packages:

`npm outdated -g --depth=0`

`npm update -g`

Update single package:

`npm outdated -g --depth=0`

`npm update -g <package_name>`

Uninstall:

`npm uninstall -g <package_name>`

List global packages:

`npm list -g --depth 0`
