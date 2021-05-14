# ember-template-lint-plugin-peopleconnect

[![npm version](https://badge.fury.io/js/ember-template-lint-plugin-peopleconnect.svg)](https://badge.fury.io/js/ember-template-lint-plugin-peopleconnect)

[PeopleConnect](http://peopleconnect.us/) shareable [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint) plugin

### Installation

```
npm install --save-dev ember-template-lint-plugin-peopleconnect
ember install ember-template-lint
```

Then inside of your newly generated `/.template-lintrc.js`:

```js
module.exports = {
  plugins: ['ember-template-lint-plugin-peopleconnect'],
  extends: 'peopleconnect:recommended'
};
```
