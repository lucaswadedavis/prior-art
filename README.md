# Prior Art

Like a bibliography for inspiration.

## How to Use:

Install with `npm install --save-dev prior-art`, then be fancy and add
`"prior-art": "node node_modules\/prior-art\/server.js"` to the `scripts`
object in your package.json, so any time later you can run
`npm run prior-art` from the root-directory of your project and it will
fire up the prior-art GUI server on `localhost:8081` and write your
`prior-art.json` file right to the root directory where it belongs.

## Why do this?

Because we don't really have a culture - like academia or to some extent
the art world what dignifies inspiration and prior art. This pisses a lot
of people off.

I wanted to make it super duper easy to cite your inspirations, not just
the code you depend on, and in a way that's easily machine-read later so
in a few years when this all catches on we can do cool analytics on the
whole ecosystem.

### License: MIT
