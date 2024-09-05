# Tailwind v3 Colors

Contains files that export all Tailwind v3 colors as Hex, RGB, and HSL values for use in TypeScript / JavaScript. This is meant to be copied over to your project as source files.

In `object/`, the entire set of colors is exported as an individual object.

```ts
import { colors } from "./object/hex";

colors.slate[50] // "#f8fafc"
```

In `namedExports/`, each color is individually exported to help with tree-shaking of unused colors.

```ts
import { slate50 } from "./namedExports/hex";

slate50 // "#f8fafc"
```
