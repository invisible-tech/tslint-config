*1.0.3*
> Fix: Don't enforce curly/scopes for one line conditionals for js files.

*1.0.2*
> Internal: Add support for ESLint rules through `tslint-eslint-rules` package.

> Fix: Don't enforce curly/scopes for one line conditionals.
```js
  // Allowing
  if (true) doSomething()
  else doAnother()
```

> Chore: Enforce spaces before/after curly and brackets
```js
  // Enforcing
  const A = [ 1, 2, 3 ]
  const O = { false: true }
```

*1.0.1*
> Fix main entry in package.json to point directly to tslint.json

*1.0.0*
> Bootstrap tslint-config library and publishing workflow.
