# Azure MCP Server

A Model Context Protocol (MCP) server for integrating Azure with GenAI applications.

## Overview

Microsoft Azure cloud services integration

## Features

- Comprehensive Azure API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install azure-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/azure-mcp-server.git
cd azure-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Azure API requirements.

## Quick Start

```python
from azure_mcp import AzureMCPServer

# Initialize the server
server = AzureMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
