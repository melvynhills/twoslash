<!-- twoslash: { theme: "../../../script/shiki-twoslash" } -->
### Adding Values

```twoslash include main
const a = 1
// - 1
const b = 2
// - 2
const c= 3
```

Let's talk a bit about `a`:

```ts twoslash
// @include: main-1
```

`a` can be added to another number

```ts twoslash
// @include: main-1
// ---cut---
const nextA = a + 13
```

Look what happens when you add `a + b`

```ts twoslash
// @include: main-2
// ---cut---
const result = a + b
//    ^?
```

Finally here is `c`:

```ts twoslash
// @include: main
// ---cut---
c.toString()
```