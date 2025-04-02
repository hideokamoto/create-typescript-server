# create-typescript-server ![NPM Version](https://img.shields.io/npm/v/%40modelcontextprotocol%2Fcreate-server)

A command line tool for quickly scaffolding new MCP (Model Context Protocol) servers. This is a public fork of [@modelcontextprotocol/create-server](https://www.npmjs.com/package/@modelcontextprotocol/create-server), maintained with the latest SDK updates and improvements.

## Getting Started

```bash
# Create a new server in the directory `my-server`
npx @modelcontextprotocol/create-server my-server

# With options
npx @modelcontextprotocol/create-server my-server --name "My MCP Server" --description "A custom MCP server"
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
