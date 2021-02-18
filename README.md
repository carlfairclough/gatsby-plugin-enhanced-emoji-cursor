# gatsby-plugin-emoji-cursor

Gatsby plugin to add emjois which trail behind your cursor ✨

## Install

`npm install --save gatsby-plugin-enhanced-emoji-cursor`


## How to use

```
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-plugin-emoji-cursor`,
   // These are the default options.
    options: {
      emoji: [`🥬`],
      fontSize: `80px`,
      lifeSpan: 125,
      interval: 200,
    },
  }
],
```
