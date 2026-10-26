# Slipity Pro Docs

The help site for Slipity Pro, built with [Mintlify](https://mintlify.com).

## Preview locally

```bash
npm i -g mint
mint dev
```

Then open http://localhost:3000.

## Screenshots

Every screenshot still to be taken is the placeholder at `images/placeholder.svg`, in a `<Frame>` whose caption begins **To capture:** and says what to show. Find them all with:

```bash
grep -rn "To capture:" --include=*.mdx .
```

Replace the `src` with the real image in `images/` and the caption with a short description.
