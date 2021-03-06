# formsy-react-components

[![Build Status](https://travis-ci.org/twisty/formsy-react-components.svg?branch=bootstrap-4-dev)](https://travis-ci.org/twisty/formsy-react-components)
[![npm version](https://badge.fury.io/js/formsy-react-components.svg)](https://badge.fury.io/js/formsy-react-components)
[![GitHub release](https://img.shields.io/github/release/twisty/formsy-react-components.svg)](https://github.com/twisty/formsy-react-components/releases)
[![GitHub contributors](https://img.shields.io/github/contributors/twisty/formsy-react-components.svg)](https://github.com/twisty/formsy-react-components/contributors)

**Note:** The work here on the [`master`](https://github.com/twisty/formsy-react-components/tree/master) branch is for upcoming release that supports Bootstrap 4. The source for current (1.x) releases can be found on the [`release-1.x`](https://github.com/twisty/formsy-react-components/tree/release-1.x) branch.

---

`formsy-react-components` is a selection of React components that render form elements for use in a [formsy-react](https://github.com/formsy/formsy-react) form.

The components render markup to be quickly included in a [Bootstrap 4 form](https://getbootstrap.com/docs/4.3/components/forms/). This includes a `<label>`, [help text](https://getbootstrap.com/docs/4.3/components/forms/#help-text), and some [validation styling](https://getbootstrap.com/docs/4.3/components/forms/#validation) tied to formsy’s validation state and validation messages.

## Install

To install using `yarn`:

```
yarn add formsy-react
yarn add formsy-react-components@next
```

To install using `npm`:

```
npm install --save formsy-react
npm install --save formsy-react-components@next
```

## Browser Support

This should run on browsers where both [Bootstrap](https://getbootstrap.com/docs/4.3/getting-started/browsers-devices/#supported-browsers) and [React](https://facebook.github.io/react/docs/react-dom.html#browser-support) are supported.

* *Internet Explorer:* polyfills for [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) and [Array.from](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Array/from?v=example#Polyfill) are required.

## Usage

```jsx
import { Form, Input } from 'formsy-react-components';

const MyForm = (props) => {
  return (
    <Form onSubmit={(data) => { console.log(data) }}>
      <Input
        name="firstname"
        label="What is your first name?"
      />
    </Form>
  )
}
```

## Examples

* See [examples](./examples/) for a overview on usage.

## Documentation

Documentation is a work in progress!

* For a working code example, visit the [Playground](http://twisty.github.io/formsy-react-components/playground/), then examine the [source](https://github.com/twisty/formsy-react-components/tree/master/examples/playground).
* There is some information in [/docs](https://github.com/twisty/formsy-react-components/tree/master/docs).
