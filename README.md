### A react and redux project based on Dan Abramov's 'Idiomatic Redux' video series.

#### Resources utilised:
- https://hackernoon.com/a-guide-to-tdd-a-react-redux-todolist-app-part-1-b8a200bb7091

#### Setup notes:
- .eslintrc using airbnb setup
- enable browser and jest globals in the eslintrc file to remove errors
- enzyme and react16 installation: `http://airbnb.io/enzyme/docs/installation/index.html`

#### Learning notes:
- Unhide hidden files in nerdTREE using `shift i`
- Enzyme `shallow` vs `render` vs `mount`
  - `shallow`: no children rendering, isolated
  - `render`: children rendering, no lifecycles
  - `mount`: children rendering, lifecycle methods
