# Eslint and prettier config
 
These are settings for ESLint and Prettier used by me

## Installing

1.In your project folder, run:
```
npm i -D eslint-config-shrimberg
npx install-peerdeps --dev eslint-config-shrimberg
```

2. You will see several dependencies were installed. Now, create (or update) a .eslintrc file with the following content:
{
  'extends': [
    'shrimberg'
  ]
}

3. Copy the .prettierrc file from this repository into your project folder

This repository is inspired by [leonardofaria](https://github.com/leonardofaria/eslint-config-leozera).
