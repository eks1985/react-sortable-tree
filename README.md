# React Sortable Tree

[![tree200](https://cloud.githubusercontent.com/assets/4413963/18860410/26f64de8-84b8-11e6-9284-350308eed30a.png)](https://fritz-c.github.io/react-sortable-tree/)

__Note: This is a work in progress; most of the features are not yet implemented.__

[DEMO](https://fritz-c.github.io/react-sortable-tree/)

### Features

- Works right out of the box, but is highly customizable
- No external CSS files

## Example

```jsx
import React from 'react';
import ReactSortableTree from 'react-sortable-tree';

export default React.createClass({
    render() {
        return (
            <ReactSortableTree myName="World" />
        );
    }
});

```

## Options

Property            | Type   | Default        | Required | Description
:-------------------|:------:|:--------------:|:--------:|:----------------------------------------
myName              | string | `World`        |          | Name of person/thing to greet.

## Contributing

After cloning the repository and running `npm install` inside, you can use the following commands to develop and build the project.

```sh
# Starts a webpack dev server that hosts a demo page with the component.
# It uses react-hot-loader so changes are reflected on save.
npm start

# Lints the code with eslint and my custom rules.
npm run lint

# Lints and builds the code, placing the result in the dist directory.
# This build is necessary to reflect changes if you're 
#  `npm link`-ed to this repository from another local project.
npm run build
```

Pull requests are welcome!

## License

MIT
