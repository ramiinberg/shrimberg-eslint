# Eslint and prettier config
 
These are settings for ESLint and Prettier used by me

## Installing

1. In your project folder, run:
  ```
    npm i -D eslint-config-shrimberg
    npx install-peerdeps --dev eslint-config-shrimberg
  ```
  - You will see several dependencies were installed. 

2. Install .eslint file

  - You can install and configure ESLint using this command:
  ```
    npm init @eslint/config
  ```

 - Or you could also make empty .eslintrc file

3. Now, update a .eslintrc file with the following content:
```
{
  "extends": [
    "shrimberg"
  ]
}
```

4. Copy the .prettierrc file from this repository into your project folder

5. You need to have Prettier and Eslint extension installed on visual studio code.

This repository is inspired by [leonardofaria](https://github.com/leonardofaria/eslint-config-leozera).
