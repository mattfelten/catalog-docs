> Create Catalog is a command line tool to set up Catalog for your style guide.

```hint|directive
To use Create Catalog, you need a recent version of [Node.js](https://nodejs.org/) installed on your computer (Version 8+ recommended).
```

## Installation

Install the create-catalog npm package globally:

```code
npm install -g create-catalog
```

Then use the `create-catalog` command to set up Catalog:

```code
create-catalog <directory>
```

Create Catalog will install everything that's necessary to run Catalog and then display instructions for using it.


#### With npx

If you have npm >= 5.2.0 (check with `npm -v`), you can use `npx` to skip the manual installation step.

```code
npx create-catalog <directory>
```

#### With yarn

If you're using [yarn](https://yarnpkg.com/) (>= 0.25) instead of npm, you can also skip the manual installation step.

```code
yarn create catalog <directory>
```
