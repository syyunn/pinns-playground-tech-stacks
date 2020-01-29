## Fronted
### Stateful UI Components 
`React` f. ui-component-wise development
`React + Typescript` f. strict type checking. Check CRA w. Typescript with [this link](https://create-react-app.dev/docs/adding-typescript/). `React + Typescript` complements the loosely typed & error-prone character of vanilla javascript that deteriorates the productivity in collobarative situation.
`React-redux` f. clean-handling o. state-sharing between components. To understand how global-stroing of local-states could lead to clean-code, check [official-example-of-react-redux](https://codesandbox.io/s/9on71rvnyo)

### Styles

#### Style-baseline
`Tachyons` f. basic-styles. All styles shall be a superset of this baseline. F. customization, shall use [tachyons-css/generator](https://github.com/tachyons-css/generator). T. visually understand tachyons, please refer t. [tachyons-tldr](https://tachyons-tldr.now.sh/#/scales#Typography)

#### Styleguide
`Storybook` f. isolated-UI-components-development & [Component-Driven Development (CDD)](https://blog.hichroma.com/component-driven-development-ce1109d56c8e) & [Visual-Test-Driven-Development](https://blog.hichroma.com/visual-test-driven-development-aec1c98bed87). Moreover, we'll hightly rely on the `addOn(s)`, one of the core features of the `Storybook`. For example, to build the responsive UI, we will use `Addon-viewport` to test the components' compatibility with the expected viewport(s). For the compatibility issue of `addOn(s)` to the react, please refer to [this-link](https://github.com/storybookjs/storybook/blob/master/ADDONS_SUPPORT.md)

### Testing
`Jest`as basic testing framework. For react-specific testing convention, follow [this-guides](https://jestjs.io/docs/en/tutorial-react). For the core functionalities we are expecting to the Jest, please refer to [this link](https://flaviocopes.com/jest/) first, rather than official guides.


## Visualization
Includes viuslization of dynamic change of weights/bias of `NN` while on training. For refernce of on-spot visualization while on traning, check [tf-playground](https://playground.tensorflow.org/)
### Libraries
`D3`

`Observalbes`

