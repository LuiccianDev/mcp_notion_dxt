
# MCP Notion

Este proyecto integra MCP Server con Notion de forma local, utilizando el empaquetador DXT para Claude Desktop.

## Descripción

Permite conectar y sincronizar datos entre MCP Server y Notion, facilitando la gestión y automatización de flujos de trabajo.

## Estructura del proyecto

- `manifest.json`: Archivo de configuración principal.

## Requisitos

- Node.js
- Instalar la extensión DXT con el siguiente comando:

```bash
npm install -g @anthropic-ai/dxt
```

Para más información sobre DXT visita [DXT en GitHub](https://github.com/anthropics/dxt).

## Instalación

## Uso

1. Clona este repositorio en tu máquina local.
2. Configura el archivo `manifest.json` según tus necesidades.
3. Obtén y agrega tus credenciales de Notion en la configuración.
4. Empaqueta la extensión ejecutando:

    ```bash
    dxt pack
    ```

    Esto generará el archivo `.dxt`.

5. Instala el archivo `.dxt` en Claude Desktop desde Configuraciones > Extensiones > Configuración avanzada > Instalación de extensión. Luego te pedirá que indiques tus credenciales de Notion.
6. Inicia MCP Server y verifica la integración con Notion.

Para más detalles sobre credenciales y configuración, consulta el proyecto original [Notion MCP Server](https://github.com/makenotion/notion-mcp-server).

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo [LICENSE](./LICENSE) para ver los términos completos.

Parte del código y la integración se basan en el proyecto original [Notion MCP Server](https://github.com/makenotion/notion-mcp-server), que también utiliza la licencia MIT y cuyo copyright es de Notion Labs, Inc. Si reutilizas o modificas este código, debes mantener los avisos de copyright y respetar los términos de la licencia MIT del proyecto fuente.
