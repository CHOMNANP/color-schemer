# Color Schemer

**[styled-components.com/color-schemer](https://styled-components.com/color-schemer/)**

A demo React app built with [`💅 styled-components`](https://github.com/styled-components/styled-components) and [`✨ polished`](https://github.com/styled-components/polished).

## Structure

Every component has a folder beneath the `src/` folder, with an `index.js` containing the component and a `style.js` containing the styled components used within that component.

```sh
colors
├── App
├── Tile
├── Tiles
├── global-styles.js # The global styles
└── index.js
```

```
┌───────────────────────────────────────────────────────────────────┐
│                              <App />                              │
│┌─────────────────────────────────────────────────────────────────┐│
││                                                                 ││
││                                                                 ││
││                           <BigTile />                           ││
││                                                                 ││
││                                                                 ││
│└─────────────────────────────────────────────────────────────────┘│
│┌─────────────────────────────────────────────────────────────────┐│
││ <Tiles />                                                       ││
││┌───────────┐┌───────────┐┌───────────┐┌───────────┐┌───────────┐││
│││           ││           ││           ││           ││           │││
│││ <Tile />  ││ <Tile />  ││ <Tile />  ││ <Tile />  ││ <Tile />  │││
│││           ││           ││           ││           ││           │││
││└───────────┘└───────────┘└───────────┘└───────────┘└───────────┘││
│└─────────────────────────────────────────────────────────────────┘│
└───────────────────────────────────────────────────────────────────┘
```

## Calculation

We take the entered color, convert it to HSL and render the same hue and saturation with lightness' of `0.1`, `0.3`, `0.5`, `0.7` and `0.9`.

## Uses

- [`create-react-app`](https://github.com/facebookincubator/create-react-app)
- [💅 `styled-components`](https://github.com/styled-components/styled-components)
- [✨ `polished`](https://github.com/styled-components/polished)
- [clipboard.js](https://clipboardjs.com/)
- [`color-name`](https://npm.im/color-name)

## License

Copyright (c) 2017 Maximilian Stoiber. Licensed under the MIT License, see the [LICENSE](LICENSE) file for more information.
