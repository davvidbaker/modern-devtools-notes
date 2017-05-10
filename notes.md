
# images 🌆
- use `srcset` attribute for multiple image sizes
  - still use `src` for old browsers
  - `sizes` too
- placeholder images from [http://placehold.it]()
- [responsive image linter](https://github.com/ausi/respimagelint)


# monitoring performance ⚡️
- [`performance` api](https://developer.mozilla.org/en-US/docs/Web/API/Performance) in browser console, eg:
  ```
  performance.getEntriesByType('resource')
  ```
- [User Timing API](https://developer.mozilla.org/en-US/docs/Web/API/User_Timing_API)
  - sub-millisecond resolution (compared to ms resolution of using `Date`)
  - more performant than `console.time()` and `console.timeEnd()`;
  - Nolan Lawson's [marky](https://github.com/nolanlawson/marky) module (mostly useful because of the browser support fallback it does)
  - metrics show up in DevTools timeline