# Router

A `<Router>` is the main [context
provider](https://reactjs.org/docs/context.html#contextprovider) in a React
Router app, which means it should typically be rendered at or near the root of
your app.

You typically do not need to render a `<Router>` directly. Instead, you'll
usually render one of the higher-level wrappers like
[`<BrowserRouter>`](browser-router.md), [`<StaticRouter>`](static-router.md), or
[`<NativeRouter>`](native-router.md) depending on your environment.

A `<Router>` accepts the following props:

<pre>
interface RouterProps {
  <a href="#router-children">children</a>?: <a href="#TODO">React.ReactNode</a>;
  <a href="#router-action">action</a>?: <a href="#TODO">Action</a>;
  <a href="#router-location">location</a>: <a href="location.md">Location</a>;
  <a href="#router-navigator">navigator</a>: <a href="#TODO">Navigator</a>;
  <a href="#router-pending">pending</a>?: boolean;
  <a href="#router-static">static</a>?: boolean;
}
</pre>

## `<Router children>`

The children element(s) for this router.

## `<Router action>`

TODO

## `<Router location>`

TODO

## `<Router navigator>`

TODO

## `<Router pending>`

TODO

## `<Router static>`

TODO
