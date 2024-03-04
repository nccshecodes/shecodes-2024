<!-- TODO: Netlify build badge -->
<!-- [![]()]() -->

<!-- TODO: Temp project link -->
<!-- Project link: [shecodes.dev](https://www.shecodes.dev) -->

## SheCodes

This project is a complete overhaul of my personal website, previously built in Eleventy. The front end landscape is ever-shifting and I despair sometimes at what the real cost of the speed of releases of new shiny things truly is. The number of hours/days/weeks lost trying to fix dependency and feature release bugs - I gave up keeping track. I just want to get back to writing HTML, CSS and Javascript. Astro ticks my boxes while I continue to think on performance, security, tooling and testing.

As ever, no doubt I will break, pull apart and put this site back together many times to come.

## Project config

- [Astro](https://astro.build/)
- [Typescript](https://www.typescriptlang.org/)
- [CSS-Modules](https://github.com/css-modules/css-modules)
- [Netlify](https://www.netlify.com/)

## Installation

This project requires Node (^18) and pnpm (^7)

To install the project dependencies:

```
pnpm install
```

### Running locally

To launch the server:

```
pnpm dev
```

Go to http://localhost:3421

<!-- ### Running production build locally

To launch the server using the production build:

```
yarn run production
cd dist && npx serve
```

Go to http://localhost:5000 -->

## Usage

### Blogposts

Content creation guidelines coming soon.

### Fonts

<!-- This project uses custom font subsets with a limited set of glyphs to keep file sizes small. Each font has a `demo.html` file inside the [font-documentation](/font-documentation) folder which can be viewed in the browser. The `glyphs & languages` tab lists each available glyph with its unicode. -->

### Images

<!-- Images are handled by the eleventy [image plugin](https://www.11ty.dev/docs/plugins/image/). The plugin performs build-time image transformations for both vector and raster images. -->

### Styling



#### CSS reset

<!-- This project uses [modern-css-reset](https://github.com/hankchizljaw/modern-css-reset). More information on the reset can be found [here](https://hankchizljaw.com/wrote/a-modern-css-reset/). -->


## Testing

### Linting and code formatting

<!-- Formatting is managed by [Prettier](https://prettier.io/).

Code-quality is managed by [ESLint](https://eslint.org/) and [Stylelint](https://stylelint.io/). -->

### Accessibility

<!-- Github action workflow `pa11y.yml` is triggered on each new PR. It runs CI accessibility tests against urls taken from an auto generated `sitemap.xml` managed by [pa11y](https://github.com/pa11y/pa11y-ci). -->

#### Note

<!-- Automated accessibility testing does not catch all errors. Manual testing is required also. -->

### Typechecking

Typescript to be implemented.

### Unit Tests

Testing framework to be implemented.

### Visual

To be implemented

## Production

The site is hosted on netlify. Production build is updated each time a pull request is merged into the main branch.