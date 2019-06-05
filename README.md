# eslint-config-danbriggs5-react
ESLint config that builds on top of [eslint-config-danbriggs5-base](https://www.npmjs.com/package/eslint-config-danbriggs5-base).

## Installation
```shell
# Install
npm install --save-dev --save-exact eslint-config-danbriggs5-react

# Install peer deps
npm install --save-dev --save-exact eslint@5.16.0
npm install --save-dev --save-exact eslint-plugin-import@2.16.0
npm install --save-dev --save-exact eslint-plugin-react@7.13.0
```

## Sample usage
Create a .eslintrc.js file
```shell
touch .eslintrc.js
open .eslintrc.js
```
Paste this snippet in your file
```javascript
module.exports = {
	extends: ['danbriggs5-react'],
};
```
## License
MIT
