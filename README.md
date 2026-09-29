# Styled Button

A small React application that demonstrates a self-contained styled button. The
page renders a centered heading and a button with inline styles and hover
feedback. Clicking the button disables it and updates its appearance.

## Why this project is useful

- Shows how to apply styles directly to React elements.
- Demonstrates hover behavior with DOM event listeners.
- Provides a minimal Create React App project for experimenting with React
  components.
- Includes a Jest and React Testing Library setup for adding component tests.

## Getting started

### Prerequisites

- Node.js and npm

### Installation

Clone the repository, move into the project directory, and install its locked
dependencies:

```bash
git clone https://github.com/VoidLance/course-files-javascript-react-styled-button.git
cd course-files-javascript-react-styled-button
npm ci
```

### Run the app

Start the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in a browser. The page
reloads automatically when source files change.

### Use the component

The example page renders `StyledButton` from
[`src/StyledButton.js`](src/StyledButton.js):

```jsx
import StyledButton from './StyledButton';

function App() {
  return <StyledButton />;
}
```

The button starts enabled, changes color while hovered, and becomes disabled
after it is clicked.

### Test and build

Run the test suite in watch mode:

```bash
npm test
```

Create an optimized production build in `build/`:

```bash
npm run build
```

## Project structure

```text
src/
├── App.js             # Application entry component
├── StyledButton.js    # Styled button example
├── App.css            # App-level styles
└── App.test.js        # React Testing Library test
public/                # Static assets and HTML template
```

## Getting help

For questions or reproducible bugs, [open an issue](../../issues/new) with
details about your environment, the steps to reproduce the problem, and any
relevant error output. For React and Create React App usage, see the
[React documentation](https://react.dev/) and
[Create React App documentation](https://create-react-app.dev/docs/getting-started/).

## Contributing

Contributions are welcome. Before opening a pull request:

1. Create a focused branch from the current default branch.
2. Make the smallest change that addresses the issue or improvement.
3. Run `npm test` and `npm run build`.
4. Explain the change and validation performed in the pull request.

Please use the issue tracker for larger proposals so they can be discussed
before implementation.

## Maintainer

This project is maintained by [VoidLance](https://github.com/VoidLance).

## License

No license file is currently included. Contact the maintainer before
redistributing or reusing the project.
