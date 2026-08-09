# CRScube API

Public API reference for CRScube clinical trial products.

**https://crscube-dev.github.io/crscube-api/**

| Product | Operations | Reference | OpenAPI |
|---------|-----------:|-----------|---------|
| CDMS API | 11 | [English](https://crscube-dev.github.io/crscube-api/en/cdms/) · [한국어](https://crscube-dev.github.io/crscube-api/cdms/) | [`cdms.en.json`](specs/cdms.en.json) · [`cdms.json`](specs/cdms.json) |
| CTMS External API | 14 | [English](https://crscube-dev.github.io/crscube-api/en/ctms/) · [한국어](https://crscube-dev.github.io/crscube-api/ctms/) | [`ctms.en.json`](specs/ctms.en.json) · [`ctms.json`](specs/ctms.json) |

Every page is available in English and Korean. Files marked `.en` carry English
descriptions; the others are Korean.

The documents under `specs/` are bundled single-file OpenAPI 3.0.3
specifications, published as both JSON and YAML. Import them directly into
Swagger UI or Postman, or generate a client SDK from them.

```bash
curl -O https://crscube-dev.github.io/crscube-api/specs/cdms.en.json
```

**Reading them in a browser:** open the JSON. GitHub Pages serves `.yaml` as
`text/yaml` without a charset, so a browser may guess the wrong encoding and
garble non-ASCII text. The YAML bytes themselves are valid UTF-8 and work
correctly with every tool — the problem is limited to viewing raw YAML in a
browser.

## Access

Credentials and host addresses are issued per integration. Contact
api-support@crscube.com to request access.

## About this repository

This repository holds generated documentation only — rendered reference pages
and bundled specs. It is published automatically; please do not edit files here
by hand. To report an error in the documentation, email api-support@crscube.com.

## License

Copyright (c) CRScube Co., Ltd. All Rights Reserved.

These documents are provided for the purpose of integrating with CRScube
products. Redistribution or modification without prior written permission is
not permitted.
