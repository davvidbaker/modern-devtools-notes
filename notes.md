
# images 🌆
- use `srcset` attribute for multiple image sizes
  - still use `src` for old browsers
  - `sizes` too
- placeholder images from [http://placehold.it]()
- [responsive image linter](https://github.com/ausi/respimagelint)


# performance ⚡️
- [`performance` api](https://developer.mozilla.org/en-US/docs/Web/API/Performance) in browser console, eg:
  ```
  performance.getEntriesByType('resource')
  ```