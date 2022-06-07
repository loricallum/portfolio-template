# Mate Portfolio

This is site is built with the [gatsby-starter-mate](https://github.com/EmaSuriano/gatsby-starter-mate). Credit to [EmaSuriano](https://github.com/EmaSuriano) for his work.

This starter is totally content based on [Contentful](https://contentful.com), which is a headless CMS where you can write the content for your page. In summary, Contentful is the Model when Gatsby with React is the View.

## Features 🛠

- [Gatsby](https://www.gatsbyjs.org/)
- [Rebass](https://rebassjs.org/): styled component system
- [React Awesome Reveal](https://github.com/dennismorello/react-awesome-reveal)
- Typescript
- CMS Integration with [Contentful](https://contentful.com)
- PWA ready
- SEO
- Responsive design
- Icons from [font-awesome](https://fontawesome.com/)
- [Netlify](https://www.netlify.com) Deployment Friendly
- Medium integration
- Social sharing (Twitter, Facebook, Google, LinkedIn)
- Developer tools:
  - `eslint`
  - `prettier`
- Google Analytics integration
- End to End with Cypress:
  - A11y testing with [Axe](https://www.deque.com/axe/)
  - Visual Testing with [Percy](https://percy.io/)

## Theming 🎨

This starters come with a hand-made color palette made by myself, but I highly encourage you to go and customize the colors to match your preference! The colors can be found inside [`theme.ts`](./src/theme.ts), which are going to be loaded by `ThemeProvider` of `styled-components` and apply across all the components inside the application.

```javascript
// colors.js
module.exports = {
  background: '#FFFFFF',
  backgroundDark: '#f0e6f6',

  text: '#333333',

  primary: '#7c37ad',
  primaryLight: '#ae66df',
  primaryDark: '#4b007d',

  secondary: '#ff4081',
  secondaryLight: '#ff79b0',
  secondaryDark: '#c60055',
};
```

Some examples I made by using palettes from [Color Hunt](https://colorhunt.co/):

![Theming](./media/theming.png)

## Tracking with Google Analytics (Optional) 📈

This starter has the analytics plugin inside the `gatsby-config`, so the only need to do in order to enable it is to provide the `Tracking Id` for your site (starts with `UA-`). Just set a new variable inside your `.env` file called `ANALYTICS_ID` and analytics will be turn on automatically 😄

## Setup 💡

```bash
# Install in case there is any new dependency added to the starter
$ yarn

# Build the project to see if everything is working as expected
$ yarn build
```

## License 📝

MIT.
