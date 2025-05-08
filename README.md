# First MCP Server -> Leave Management

This AI tool helps an HR with leave management related tasks. This code will interact with MCP server & a mock database and responds to MCP client queries.

## Setup

1 Install Claude Desktop (FREE VERSION or PAID VERSION)

2 Install uv by running
```bash
pip install uv
```
3 Run the below command to create a project directory.
```bash
uv init my-first-mcp-server 
```
4 Run the below command to add mcp cli in your project
```bash
uv add "mcp[cli]"
```
5 Few folks may get type errors for which you can run the following command to upgrade typer library.
```bash
pip install --upgrade typer
```
