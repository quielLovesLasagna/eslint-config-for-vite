# eslint-config-for-vite
Configuration for ESLint (RED LINE WARNING) 

When there is an unused variable, by default react views it as an error. To fix: 

- Open the Eslint Configuration (.eslintrc.cjs)

- Paste the code inside the Rules:

```js
"no-unused-vars": "warn",
"react/prop-types": "off",
```



    
