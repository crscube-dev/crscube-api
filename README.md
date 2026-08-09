# CRScube API

Public API reference for CRScube clinical trial products.

**https://crscube-dev.github.io/crscube-api/**

| Product | Operations | Reference | OpenAPI |
|---------|-----------:|-----------|---------|
| CDMS API | 11 | [/cdms/](https://crscube-dev.github.io/crscube-api/cdms/) | [`specs/cdms.yaml`](specs/cdms.yaml) |
| CTMS External API | 14 | [/ctms/](https://crscube-dev.github.io/crscube-api/ctms/) | [`specs/ctms.yaml`](specs/ctms.yaml) |

The specs under `specs/` are bundled single-file OpenAPI 3.0.3 documents. Import
them directly into Swagger UI or Postman, or generate a client SDK from them.

```bash
curl -O https://crscube-dev.github.io/crscube-api/specs/cdms.yaml
```

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
