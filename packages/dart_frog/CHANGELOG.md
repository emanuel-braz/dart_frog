# 0.3.2

- feat: cache `Request` and `Response` body

# 0.3.1

- feat: add `formData` to `Request`/`Response`

# 0.3.0

- **BREAKING** fix: `Request.json()` and `Response.json()` return `Future<dynamic>`

# 0.2.0

- **BREAKING** feat: support mounting dynamic routes
- **BREAKING** deps: upgrade to `Dart ">=2.18.0 <3.0.0"`
- deps: upgrade to `very_good_analysis ^3.1.0`

# 0.1.2

- feat: add x-powered-by-header to `serve`

# 0.1.1

- fix: update `Response.json` headers to `<String, Object>`

# 0.1.0

- chore: stable 0.1.0 release

# 0.0.1-dev.12

- feat: expose `HttpConnectionInfo` on `Request`
- chore: upgrade to very_good_analysis v3.0.1

# 0.0.1-dev.11

- fix: Request/Response `headers` is of type `Map<String, String>`
- docs: pubspec `homepage`, `repository`, `issue_tracker`, and `documentation` links

# 0.0.1-dev.10

- fix: Response `json()` returns `Object?`
- fix: provider `StateError` message typo

# 0.0.1-dev.9

- feat: expose `fromShelfHandler` and `fromShelfMiddleware` adapters

# 0.0.1-dev.8

- feat: add `createStaticFileHandler`
- feat: add `Cascade`

# 0.0.1-dev.7

- fix: hot reload stability improvements and error reporting

# 0.0.1-dev.6

- feat: expand router http method support

# 0.0.1-dev.5

- feat: change `Response.json` body to type `Object?`

# 0.0.1-dev.4

- fix: support multiple routeNotFound.read calls
  - resolves: `bad state: The 'read' method can only be called once`

# 0.0.1-dev.3

- docs: add example and improve documentation

# 0.0.1-dev.2

- docs: fix README assets

# 0.0.1-dev.1

- feat: initial experimental release 🎉
