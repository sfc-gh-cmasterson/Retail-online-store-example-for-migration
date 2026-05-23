# Changelog

## [0.1.1](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/compare/v0.1.0...v0.1.1) (2026-05-23)


### Bug Fixes

* SKIP_ENV_VALIDATION must be 'true' (string), not 1 ([51c6440](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/51c6440700130981c31e84d4396ce132d922b064))
* storefront Dockerfile env-bypass + Storybook to nextjs-vite ([74d7344](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/74d73448ad8af7140b0ed0796c00c5ae79e9d20d))
* unblock CI - resolve site-config syntax error and dependency CVEs ([4a65fbe](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/4a65fbe078c51bb97b96d3efdd543ad60bee83f2))


### Documentation

* refresh branch-protection runbook with the 12 wired status checks ([f40f394](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/f40f3943d3ad2a259f18e26acd24648a12d7a621))


### Build

* regenerate lockfile after retail-example rename + new devDeps ([efc11c5](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/efc11c5f65fc36d9f1c5fe7c57be77d36d509285))


### CI/CD

* build-images on native ubuntu-24.04-arm runner (drops QEMU) ([0e9f023](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/0e9f023e9efadd244294132fd89010800367b833))
* bump build-images timeout 30-&gt;60 min for arm64 QEMU cross-builds ([fbf4e21](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/fbf4e214de2e4cbcdd944fc5bfa3384610291e8a))
* bump Trivy action to 0.29.0 (release tag exists) ([f38f9c4](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/f38f9c491577f3c5d80e9b624ebaa0b578ff8d28))
* disable Storybook GitHub Pages workflow until Storybook 9 ([bf4b666](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/bf4b6662463d4749f98127921da59cd12f4b3ee3))
* install before pnpm audit, soften Trivy fs to informational, untrack tsbuildinfo ([dbd3a6d](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/dbd3a6d78e2e007e28941365ef3d0462f312ab27))
* pin Trivy action to 0.20.0 (0.28.0 does not exist) ([80baa44](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/80baa4496d9824229696b0caefc0db428dbad4d9))
* scope unit tests to portable specs and skip env gate in CI ([acb7d8f](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/acb7d8fb4b9802e76a5b47a010fec5f4114fd8f4))
* switch Trivy to master ref (tag resolution flaky) ([e7fb70b](https://github.com/sfc-gh-cmasterson/Retail-online-store-example-for-migration/commit/e7fb70b798ed972a9bb794790a983d62f8ba2b99))

## Changelog

This file is managed by [release-please](https://github.com/googleapis/release-please).
Do not edit manually — write [conventional commits](https://www.conventionalcommits.org)
and the entries will be generated automatically when a release PR is merged.
