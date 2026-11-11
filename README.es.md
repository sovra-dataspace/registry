# Registro de módulos de Sovra

[English](README.md) · **Español**

El registro firmado de módulos de Sovra: los módulos WebAssembly instalables del conector de espacios de datos Sovra (PostgreSQL, S3/MinIO, NGSI-LD…), publicados como ficheros del release [`registry`](https://github.com/sovra-dataspace/registry/releases/tag/registry). Los conectores los descargan de:

```text
https://github.com/sovra-dataspace/registry/releases/download/registry/
```

Cada módulo y el índice van firmados con la clave de Sovra; los conectores comprueban la firma antes de instalar. Aquí no se edita nada a mano: lo publica el release de [dataspace-addons](https://github.com/sovra-dataspace/dataspace-addons).
