# styled-jumbotron-component

> The [bootstrap](https://getbootstrap.com) jumbotron component made with [styled components](https://styled-components.com) and [styled-system](http://jxnblk.com/styled-system/)

## Table of Contents

* [Documentation with Storybook](https://aichbauer.github.io/react-styled-bootstrap-components)
* [Why?](#why)
* [Installation](#installation)
* [Usage](#usage)
* [Properties](#properties)
* [Related](#related)
* [License](#license)

## Why?

This is a modular approach to use [bootstrap](https://getbootstrap.com) components for quick prototypes, as an entrypoint of your own component library, or if you need just one [bootstrap](https://getbootstrap.com) component for your application. To work with ease with any other libary or framework this component is build with [styled components](https://styled-components.com) and [styled-system](http://jxnblk.com/styled-system/).

## Installation

```sh
$ npm i styled-jumbotron-component -S
```

or

```sh
$ yarn add styled-jumbotron-component
```

## Usage

For more detailed information take a look at the [documentation with Storybook](https://aichbauer.github.io/react-styled-bootstrap-components).

```jsx
import { Jumbotron } from 'styled-jumbotron-component';

const MyButtonComponent = (props) => (
  {/* use different props to change the visual appearance */}
  <Jumbotron fluid>
    <h1>
    Fluid jumbotron
    </h1>
    <p>
      This is a modified jumbotron that occupies the entire horizontal space of its parent.
    </p>
  </Jumbotron>
);
```

## Properties

Properties which can be added to the component to change the visual appearance.

* `fluid` **Type**: boolean
* `m`  margin **Type**: string
* `mt` margin-top **Type**: string
* `mr` margin-right **Type**: string
* `mb` margin-bottom **Type**: string
* `ml` margin-left **Type**: string
* `mx` margin-left and margin-right **Type**: string
* `my` margin-top and margin-bottom **Type**: string
* `p`  padding **Type**: string
* `pt` padding-top **Type**: string
* `pr` padding-right **Type**: string
* `pb` padding-bottom **Type**: string
* `pl` padding-left **Type**: string
* `px` padding-left and padding-right **Type**: string
* `py` padding-top and padding-bottom **Type**: string
* `width` **Type**: string
* `fontSize` **Type**: string
* `fontWeight` **Type**: string
* `textAlign` **Type**: string
* `lineHeight` **Type**: string
* `display` **Type**: string
* `color` **Type**: string
* `borderRadius` **Type**: string
* `borderColor` **Type**: string
* `border` **Type**: string
* `borderTop` **Type**: string
* `borderRight` **Type**: string
* `borderBottom` **Type**: string
* `borderLeft` **Type**: string

## Related

[bootstrap](https://getbootstrap.com)
[styled components](https://styled-components.com)
[styled-system](http://jxnblk.com/styled-system/)

## License

MIT © Lukas Aichbauer