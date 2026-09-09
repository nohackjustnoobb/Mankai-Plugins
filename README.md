# Mankai Plugins

This repository contains JavaScript plugins for [mankai](https://github.com/nohackjustnoobb/mankai).

You can find the compiled plugins in the [static branch](https://github.com/nohackjustnoobb/mankai-plugins/tree/static).

## Documentation

See the [JavaScript Plugin API documentation](https://github.com/nohackjustnoobb/mankai/blob/master/docs/jsplugin/api.md) for details about the runtime, plugin metadata, and available APIs.

## Development

This project uses [Bun](https://bun.sh/).

Install dependencies with:

```bash
bun install
```

### Creating a New Plugin

To develop a new plugin, copy the `src/template` directory to a new directory under `src/` (e.g., `src/my-plugin`), and replace the implementation with your own.

### Build

To build the plugins:

```bash
bun run build
```

This will generate the output in the `dist/` directory.

### Dev

To run in development mode:

```bash
bun run dev
```

## Disclaimer

The developers of this project do not assume any responsibility for how these plugins are used. This code is provided for educational and research purposes only. Users are solely responsible for their actions and must ensure they comply with all applicable laws and regulations.
