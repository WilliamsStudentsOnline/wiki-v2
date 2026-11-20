# WSO Developer Wiki

Docs and dev blog for WSO, built with [Hugo](https://gohugo.io) and the [Hextra](https://imfing.github.io/hextra/) theme. Served at https://wso-dev.williams.edu/wiki/.

Sensitive info (credentials, server internals) lives in the private Google Drive, not here. This repo is public.

## Local dev

Requires Hugo (extended) and Go.

```sh
brew install hugo go
hugo server
```

Then open http://localhost:1313/wiki/.

## Writing

- Docs go in `content/docs/`; order pages with `weight:` in frontmatter
- Blog posts go in `content/blog/`
- Images and files go in `static/`

## Deploy

Pushing to `main` builds and deploys to wso-dev via the self-hosted runner.
