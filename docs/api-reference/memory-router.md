# MemoryRouter

A `<MemoryRouter>` is a [`<Router>`](router.md) that manages the location using
an in-memory history stack. This makes it ideal for use in situations where you
either don't have a web browser (like [React Native](https://reactnative.dev/))
or in tests.

A `<MemoryRouter>` accepts the following props:

<pre>
interface MemoryRouterProps {
  <a href="#memoryrouter-children">children</a>?: <a href="#TODO">React.ReactNode</a>;
  <a href="#memoryrouter-initialentries">initialEntries</a>?: <a href="#TODO">InitialEntry</a>[];
  <a href="#memoryrouter-initialindex">initialIndex</a>?: number;
}
</pre>

## `<MemoryRouter children>`

The children element(s) for this router. See [`<Router
children>`](router.md#routerchildren)

## `<MemoryRouter initialEntries>`

TODO

## `<MemoryRouter initialIndex>`

TODO
