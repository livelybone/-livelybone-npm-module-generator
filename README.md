# @livelybone/npm-module-generator
A plugins for generating a framework of npm module, include directories and dependencies.

The module is based on template, welcome to add more templates.

## repository
https://github.com/livelybone/-livelybone-npm-module-generator.git

## Demo
https://github.com/livelybone/-livelybone-npm-module-generator#readme

## installation
```bash
npm i -g @livelybone/npm-module-generator
```

## Use
```bash
module-generator [projectName] [--template] [cmd]
```

## Options
|Argument|Default|Description|
|--------|-------|-----------|
|`projectName`|none|Optional. ProjectName, dirname|
|`template`|`--js-plugin`|Optional. Chose template, options: `['--vue-plugin', '--js-plugin']`|
|`cmd`|none|Optional. `-v` `--v` `-version` `--version` -> version |
