# Code Snippets Library — product truth

> Product truth inferred from the existing README, routes, data file, and implementation because this batch was explicitly authorized to proceed without an interview.

## Purpose

An authored code specimen library that makes a small set of reusable snippets discoverable through a portfolio surface and exposes the MCP endpoint honestly.

## Current behavior

- The main page presents MCP tool affordances for `get_all`, `get_by_id`, and `search`.
- The repo includes a small authored local data file with React and Python examples and category metadata.
- The `/api/mcp` route accepts JSON-RPC-like requests for initialize, tool listing, and a transparent tool-call echo response.
- The current surface is a showcase and protocol boundary; it is not a full remote snippet database, auth system, sync service, or claim of production MCP completeness.

## Boundaries

Keep the visual system centered on reading, copying, and understanding code. Label demo data and protocol behavior clearly so the page does not overstate the library's scale or server capabilities.
