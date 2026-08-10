# BIMeta Releases

Official installer downloads for BIMeta desktop products, published by
BIMeta Corporation (https://www.bimeta.net).

- Each product's releases are tagged `{product-id}-v{version}` with the
  signed installer attached as an asset.
- `manifests/{product-id}.json` describes the latest version of each
  product; installed BIMeta apps poll these files to offer updates.

This repository contains no source code. Installers are Authenticode-signed;
verify the signature and the SHA-256 in the manifest after downloading.
