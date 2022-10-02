# --Insert Laundry-Related Pun Here--

## Let's Learn an ESLint Rule
Here, the ESLint's "semi" rule is set to recognize missing semicolons as errors. While JavaScript's engine will automatically insert semicolons when it recognizes the end of a statement using a feature called **Automatic Semicolon Insertion**, or **ASI**, there are some situations in which it is possible to omit a semicolon in a way that may be misinterpreted by the JavaScript engine. This can result in errors or other undesirable behavior. These errors can be difficult to find as they are often syntactically "correct", and using ESLint to enforce the consistent use of semicolons throughout a project can help prevent them.

[ESLint.org Docs: semi](https://eslint.org/docs/latest/rules/semi)