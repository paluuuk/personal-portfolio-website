# Personal Portfolio Website

A React 18 portfolio site presenting software, data, and engineering projects, with Chakra UI components, animation, and Markdown rendering.

## Implementation

- `src/`: React application source.
- `public/`: static web assets.
- `package.json`: Create React App development, build, and test commands.
- `yarn.lock`: the repository's dependency lockfile.
- `build/`: a committed build artifact from the original project.

The dependency set includes Chakra UI, Emotion, Framer Motion, React Bootstrap, and Markdown rendering utilities.

## Local development

```bash
git clone https://github.com/paluuuk/personal-portfolio-website.git
cd personal-portfolio-website
yarn install --frozen-lockfile
yarn start
```

The development server uses port 3000 by default.

## Build and checks

```bash
yarn build
yarn test --watchAll=false
```

These are the scripts defined by the project; this documentation update does not claim a new deployment or a freshly passing browser test suite. The toolchain is the repository's existing `react-scripts` 5 setup, so runtime compatibility should be checked before upgrading dependencies.

For the current curated project overview, start at [my GitHub profile](https://github.com/paluuuk).
