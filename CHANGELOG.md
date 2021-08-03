# Release Notes

## [Unreleased](https://github.com/laravel/breeze/compare/v1.3.2...1.x)


## [v1.3.2 (2021-08-03)](https://github.com/laravel/breeze/compare/v1.3.1...v1.3.2)

### Changed
- Update url for JS ([eba8457](https://github.com/laravel/breeze/commit/eba8457b2e16d92fb0909e6e4a36f7cf9f50bc78))
- Add Vue file extension to all Vue components imported ([#89](https://github.com/laravel/breeze/pull/89))
- Update `<Link>` tags & implement `<Head>` management (title tag) ([#90](https://github.com/laravel/breeze/pull/90), [4dce8a8](https://github.com/laravel/breeze/commit/4dce8a8c9dd1b0ca23fbe92fa51b17cc5ccd6bb5), [128fd28](https://github.com/laravel/breeze/commit/128fd28e2ebd5fde7730d90b0052d175b887568a), [#94](https://github.com/laravel/breeze/pull/94))

### Fixed
- Change from POST to GET on responsive dashboard link ([#92](https://github.com/laravel/breeze/pull/92))


## [v1.3.1 (2021-06-22)](https://github.com/laravel/breeze/compare/v1.3.0...v1.3.1)

### Fixed
- Fix EmailVerificationTest to pass using Uuids ([#85](https://github.com/laravel/breeze/pull/85))


## [v1.3.0 (2021-06-08)](https://github.com/laravel/breeze/compare/v1.2.3...v1.3.0)

### Changed
- Update Inertia ([c439176](https://github.com/laravel/breeze/commit/c43917630e9b45b78dfd805f152262e08a7d2ffb))
- Update versions ([aa90bfd](https://github.com/laravel/breeze/commit/aa90bfd5b31cedf848087d105b6924b0f120fc99))


## [v1.2.3 (2021-06-08)](https://github.com/laravel/breeze/compare/v1.2.2...v1.2.3)

### Fixed
- Fix purge line to include *.js ([#83](https://github.com/laravel/breeze/pull/83))


## [v1.2.2 (2021-06-01)](https://github.com/laravel/breeze/compare/v1.2.1...v1.2.2)

### Fixed
- Fix CORS policy errors with inertia stack ([#82](https://github.com/laravel/breeze/pull/82))


## [v1.2.1 (2021-05-25)](https://github.com/laravel/breeze/compare/v1.2.0...v1.2.1)

### Fixed
- Fix dropdown ([87e849a](https://github.com/laravel/breeze/commit/87e849a2fd635628d99aa8514e2ee9321decee27))
- Fix link type ([c83d1ac](https://github.com/laravel/breeze/commit/c83d1ac389a58f1fb9ee6491ce14488f6a0a746b))


## [v1.2.0 (2021-05-20)](https://github.com/laravel/breeze/compare/v1.1.8...v1.2.0)

### Added
- React installation option ([#73](https://github.com/laravel/breeze/pull/73))
- Use new `Password::defaults()` feature ([#71](https://github.com/laravel/breeze/pull/71))


## [v1.1.8 (2021-05-18)](https://github.com/laravel/breeze/compare/v1.1.7...v1.1.8)

### Fixed
- Bump Inertia version to match Spark ([#70](https://github.com/laravel/breeze/pull/70))


## [v1.1.7 (2021-05-11)](https://github.com/laravel/breeze/compare/v1.1.6...v1.1.7)

### Changed
- Uses password rule by default ([#65](https://github.com/laravel/breeze/pull/65))

### Fixed
- Use boolean() instead of filled() ([#68](https://github.com/laravel/breeze/pull/68))
- Fix create method docblock return value ([#69](https://github.com/laravel/breeze/pull/69))


## [v1.1.6 (2021-04-27)](https://github.com/laravel/breeze/compare/v1.1.5...v1.1.6)

### Fixed
- Fix Vue warning ([#62](https://github.com/laravel/breeze/pull/62))


## [v1.1.5 (2021-04-13)](https://github.com/laravel/breeze/compare/v1.1.4...v1.1.5)

### Fixed
- Fix Login event firing before Register ([#59](https://github.com/laravel/breeze/pull/59))


## [v1.1.4 (2021-03-23)](https://github.com/laravel/breeze/compare/v1.1.3...v1.1.4)

### Fixed
- Fixes Vue warning ([#55](https://github.com/laravel/breeze/pull/55))

### Removed
- Remove unused component ([#54](https://github.com/laravel/breeze/pull/54))


## [v1.1.3 (2021-02-18)](https://github.com/laravel/breeze/compare/v1.1.2...v1.1.3)

### Fixed
- Update stubs/inertia/app case in installInertiaStack ([#53](https://github.com/laravel/breeze/pull/53))


## [v1.1.2 (2021-02-18)](https://github.com/laravel/breeze/compare/v1.1.1...v1.1.2)

### Changed
- Add `@inertiajs/progress` to package dependencies ([#46](https://github.com/laravel/breeze/pull/46), [#49](https://github.com/laravel/breeze/pull/49))
- Reduce verbosity by introducing a 'Guest' layout ([#52](https://github.com/laravel/breeze/pull/52))
- Add email (username) autocomplete ([#51](https://github.com/laravel/breeze/pull/51))
- Simplify Inertia logout links ([#48](https://github.com/laravel/breeze/pull/48))


## [v1.1.1 (2021-02-17)](https://github.com/laravel/breeze/compare/v1.0.4...v1.1.1)

### Added
- Inertia Stack ([#44)](https://github.com/laravel/breeze/pull/44))

### Fixed
- Copy webpack.config.js on inertia init ([#45](https://github.com/laravel/breeze/pull/45))


## [v1.0.4 (2021-02-16)](https://github.com/laravel/breeze/compare/v1.0.3...v1.0.4)

### Changed
- Update Tailwind config ([de0cbf4](https://github.com/laravel/breeze/commit/de0cbf49b50c22aaf047dcaba8c83827164ff668))


## [v1.0.3 (2021-02-16)](https://github.com/laravel/breeze/compare/v1.0.2...v1.0.3)

### Fixed
- Redirect to intended path after login ([#39](https://github.com/laravel/breeze/pull/39))
- Change "Logout" text to "Log out" and "Login" to "Log in" ([#41](https://github.com/laravel/breeze/pull/41))


## [v1.0.2 (2021-01-05)](https://github.com/laravel/breeze/compare/v1.0.1...v1.0.2)

### Changed
- Upgrade to PostCSS 8 as Laravel Mix v6 is out ([#31](https://github.com/laravel/breeze/pull/31))


## [v1.0.1 (2020-12-22)](https://github.com/laravel/breeze/compare/v1.0.0...v1.0.1)

### Changed
- Reuse blade component ([#30](https://github.com/laravel/breeze/pull/30))
- Improve SPA compatibility ([#29](https://github.com/laravel/breeze/pull/29))


## v1.0.0 (2020-10-08)

Initial stable release.
