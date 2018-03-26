[![NPM version](https://badge.fury.io/js/tslint-checker.svg)](https://www.npmjs.com/package/tslint-checker)
[![Downloads](http://img.shields.io/npm/dm/tslint-checker.svg)](https://npmjs.org/package/tslint-checker)

# tslint-checker

tslint-checker is the module to synchronise linting rules in the distributed development environment.

- Works on the latest [tslint](https://palantir.github.io/tslint/rules/) rules
- Serves linting rules for Typescript, React (tsx support) and Angular projects
- Easily extensible
- Easy incorporation

## Usage
The package can be integrated very easily in any project.
```
 - npm install tslint-checker -D
```
Create a `tslint.json` file in the root folder of your project and add
the following:

``` json
{
  "extends": "tslint-checker/tslint"
}
```

### Incorporation for React projects (.tsx files)

``` json
{
  "extends": "tslint-checker/tslint-react"
}

```

### Incorporation for Angular projects

``` json
{
  "extends": "tslint-checker/tslint-ng2"
}

```

## Reference TS Lint Rules:
[TSLint Rules](https://palantir.github.io/tslint/rules/)

## License
MIT