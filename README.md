# vcpe.dev

The root GitHub Pages site of the boardfarmdevs account, served at https://vcpe.dev/.

- `index.html`: the selector: the EasyMesh labs at https://mesh.vcpe.dev/ (the easymesh-labs
  repository's own custom domain) and the apps labs at https://apps.vcpe.dev/ (the apps-labs repository's own custom domain).
- `favicon.svg`, `favicon.ico` (16/32/48) and `apple-touch-icon.png` (180): a "v" drawn as a
  three-node mesh with Wi-Fi arcs. Pages under vcpe.dev without their own icon use `/favicon.ico` too.
- `404.html`: the earlier vcpe.dev notes moved to https://revs.dev/; links to their paths
  (`/docs/`, `/lxd/`, `/rssfree/`, ...) are sent there. Anything else gets a not-found page.

Published by `.github/workflows/pages.yml` (Pages source: GitHub Actions; custom domain set in
Settings -> Pages). Every other boardfarmdevs repository with Pages is served under this domain as a path, for
example https://vcpe.dev/emosa-lab/.
