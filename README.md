# Static website generation with Hugo

This is an example of a static website generated with [Hugo](https://gohugo.io) from dev to production.

## Prerequisites

The following prerequisites must be filled to run this service:

- [Docker](https://docs.docker.com/get-docker/) must be installed.
- [Docker Compose](https://docs.docker.com/compose/install/) must be installed (it should be installed by default with Docker in most cases).
- [Visual Studio Code](https://code.visualstudio.com/download) must be installed.
- [Dev containers](https://code.visualstudio.com/docs/remote/containers) must be installed in Visual Studio Code.

## Start the application for local development

```bash
hugo server

# or

hugo server -D # to include draft posts
```


## License

This work is licensed under a
[AGPL-3.0 license ](./LICENSE.md)
license.

## Sources

- [Hugo - Get Started](https://gohugo.io/getting-started/quick-start/)
- [Hugo - Host on GitHub Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/)