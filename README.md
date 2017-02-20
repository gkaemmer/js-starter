# js-starter
Minimal boilerplate code for a ES6 module with a runnable example.

## Usage
This repo is meant to provide all necessary boilerplate to start hacking away at a new ES6 Module.

    git clone git@github.com:gkaemmer/js-starter.git YOUR_PACKAGE_NAME_HERE
    cd YOUR_PACKAGE_NAME_HERE
    rm -rf .git
    yarn # (or npm install)

Bam, you have an environment ready to go. You'll first want to replace all of the `PACKAGE_*` placeholders in `package.json` and `webpack.config.js`, to use the actual name of your module.

Once that's done, you can start building.

`yarn start`: Starts a development server that uses the `example/` directory. Hot reloading is supported.
`yarn test`: Runs tests with jest. These are the `.test.js` files in the `src/test` folder.

## Publishing
You can publish with `npm publish`.
