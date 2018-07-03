# eslint-plugin-disallow-switch-statements

An ESLint rule to totally disallow switch statements

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-disallow-switch-statements`:

```
$ npm install eslint-plugin-disallow-switch-statements --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-disallow-switch-statements` globally.

## Usage

Add `disallow-switch-statements` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "disallow-switch-statements"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "disallow-switch-statements/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here




