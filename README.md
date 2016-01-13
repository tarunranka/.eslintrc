# .eslintrc

My .eslintrc config

```
{
  "parser": "babel-eslint",
  "plugins": [
    "lw"
  ],
  "ecmaFeatures": {
  },
  "env": {
    "browser": true,
    "node": true,
    "jquery": true,
    "es6": true,
    "mocha": true
  },
  "rules": {

    "no-constant-condition": 2,
    "no-dupe-args": 2,
    "no-dupe-keys": 2,
    "no-duplicate-case": 2,
    "no-cond-assign": 2,
    "no-ex-assign": 2,
    "no-extra-semi": 2,
    "no-func-assign": 2,
    "no-inner-declarations": [2, "both"],
    "no-obj-calls": 2,
    "no-sparse-arrays": 2,
    "valid-typeof": 2,

    "curly": 2,
    "default-case": 2,
    "dot-notation": 2,
    "dot-location": [2, "property"],
    "eqeqeq": 2,
    "no-caller": 2,
    "no-else-return": 2,
    "no-eq-null": 2,
    "no-eval": 2,
    "no-extend-native": 2,
    "no-extra-bind": 2,
    "no-floating-decimal": 2,
    "no-implicit-coercion": [2,
      {
        "boolean": false,
        "number": true,
        "string": true
      }
    ],
    "no-implied-eval": 2,
    "no-invalid-this": 1,
    "no-lone-blocks": 2,
    "no-loop-func": 2,
    "no-multi-spaces": 2,
    "no-native-reassign": 2,
    "no-new-func": 2,
    "no-new-wrappers": 2,
    "no-new": 2,
    "no-param-reassign": [1, {"props": true}],
    "no-proto": 2,
    "no-redeclare": 2,
    "no-return-assign": [2, "except-parens"],
    "no-self-compare": 2,
    "no-sequences": 2,
    "no-throw-literal": 2,
    "no-useless-call": 2,
    "no-useless-concat": 2,
    "no-with": 2,
    "wrap-iife": [2, "outside"],
    "yoda": 2,

    "no-catch-shadow": 2,
    "no-delete-var": 2,
    "no-shadow-restricted-names": 2,
    "no-shadow": [2, { "hoist": "functions" }],
    "no-undef": 2,
    "no-unused-vars": 2,

    "no-new-require": 2,

    "array-bracket-spacing": [2, "never"],
    "brace-style": [2, "stroustrup", {"allowSingleLine": false}],
    "comma-spacing": [2, {"before": false, "after": true}],
    "comma-style": [2, "last"],
    "comma-dangle": [2, "never"],
    "computed-property-spacing": [2, "never"],
    "consistent-this": [2, "self"],
    "eol-last": 2,
    "indent": [0, 2, {"SwitchCase": 1}],
    "jsx-quotes": [2, "prefer-double"],
    "key-spacing": [2, {"beforeColon": false, "afterColon": true}],
    "new-parens": 2,
    "no-lonely-if": 2,
    "no-new-object": 2,
    "no-trailing-spaces": [2, { "skipBlankLines": true }],
    "object-curly-spacing": [2, "never"],
    "quotes": [2, "single", "avoid-escape"],
    "sort-vars": 2,
    "space-after-keywords": 2,
    "space-before-keywords": [2, "always"],
    "space-before-function-paren": [2, "always"],
    "space-in-parens": [2, "never"],
    "space-infix-ops": 2,
    "space-return-throw-case": 2,
    "space-unary-ops": [1, { "words": true, "nonwords": false }],

    "arrow-spacing": 2,
    "constructor-super": 2,
    "generator-star-spacing": [2, "after"],
    "no-class-assign": 2,
    "no-const-assign": 2,
    "no-dupe-class-members": 2,
    "no-this-before-super": 2,
    "no-var": 2,
    "object-shorthand": [2, "always"],
    "prefer-arrow-callback": 2,
    "prefer-spread": 2,
    "prefer-template": 2,
    "require-yield": 2,

    "max-params": [2, 6],
    "no-plusplus": 2,

    "no-console": 1,
    "no-debugger": 1,
    "semi": [1, "never"],
    "space-before-blocks": [2, "always"],
    "strict": 0,

    "lw/function-padding": 2
  }
}

```
