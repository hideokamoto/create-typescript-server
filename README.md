# create-typescript-server ![NPM Version](https://img.shields.io/npm/v/%40modelcontextprotocol%2Fcreate-server)

A command line tool for quickly scaffolding new MCP (Model Context Protocol) servers. This is a public fork of [@modelcontextprotocol/create-server](https://www.npmjs.com/package/@modelcontextprotocol/create-server), maintained with the latest SDK updates and improvements.

## Getting Started

```bash
# Create a new server in the directory `my-server`
npm create mcp-tools my-server

# With options
npm create mcp-tools my-server --name "My MCP Server" --description "A custom MCP server"
```

After creating your server:

```bash
cd my-server     # Navigate to server directory
npm install      # Install dependencies

npm run build    # Build once
# or...
npm run watch    # Start TypeScript compiler in watch mode

# optional
npm link         # Make your server binary globally available
```

```bash
% npm create mcp-tools --help
Create a package.json file

Usage:
npm init <package-spec> (same as `npx <package-spec>`)
npm init <@scope> (same as `npx <@scope>/create`)

Options:
[--init-author-name <name>] [--init-author-url <url>] [--init-license <license>]
[--init-module <module>] [--init-version <version>] [-y|--yes] [-f|--force]
[--scope <@scope>]
[-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
[-ws|--workspaces] [--no-workspaces-update] [--include-workspace-root]

aliases: create, innit

Run "npm help init" for more info
```

## Differences from the original

This fork includes:
- Updated MCP SDK to version 1.8.0
- Added Zod for input validation
- Simplified API usage with the latest best practices
- Regular maintenance and updates

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License—see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Original project: [@modelcontextprotocol/create-server](https://www.npmjs.com/package/@modelcontextprotocol/create-server)
