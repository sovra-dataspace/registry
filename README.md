# Sovra module registry

**English** · [Español](README.es.md)

Sovra's signed module registry: the installable WebAssembly modules of the Sovra data space connector (PostgreSQL, S3/MinIO, NGSI-LD…), published as the assets of the release [`registry`](https://github.com/sovra-dataspace/registry/releases/tag/registry). Connectors download them from:

```text
https://github.com/sovra-dataspace/registry/releases/download/registry/
```

Every module and the index are signed with Sovra's key; connectors check the signature before installing. Nothing is edited here by hand: the release of [dataspace-addons](https://github.com/sovra-dataspace/dataspace-addons) publishes it.
