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

**Reading them in a browser.** GitHub Pages serves `.yaml` as `text/yaml`
without a charset, so a browser guesses the encoding and garbles non-ASCII
text. The bytes are valid UTF-8 and work correctly with every tool — only raw
viewing in a browser is affected.

Open the JSON, or use the viewer at
[**/specs/**](https://crscube-dev.github.io/crscube-api/specs/), which decodes
the file as UTF-8 explicitly. A direct link works too, for example
[`/specs/?f=cdms.yaml`](https://crscube-dev.github.io/crscube-api/specs/?f=cdms.yaml).

## Access

Credentials and host addresses are issued per integration. Contact your
CRScube representative to request access.

## About this repository

This repository holds generated documentation only — rendered reference pages
and bundled specs. Please do not edit files here by hand.
To report an error in the documentation, contact your CRScube representative.

## License

Copyright (c) CRScube Co., Ltd. All Rights Reserved.

These documents are provided for the purpose of integrating with CRScube
products. Redistribution or modification without prior written permission is
not permitted.
