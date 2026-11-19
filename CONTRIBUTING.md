# Contributing

This repository is maintained by Modern AI. It is a small, focused MCP server with no build step and a narrow scope: two read-only tools and one upstream service. Please keep contributions small and inside that scope.

## Before you start

For anything larger than a small fix, open an issue first so we can agree on the change before you write it.

## Reporting a bug

Open an issue with:
- What you ran: the `tools/call` request body you sent
- What you got
- What you expected instead

Do not report security problems in a public issue. See SECURITY.md.

## Pull requests

- One change per pull request.
- Tests pass: `node --test test/*.js`
- Add or update a test when you change behavior.

## Sign your commits (DCO)

We use the Developer Certificate of Origin 1.1 (https://developercertificate.org), not a contributor license agreement. Each commit must carry a sign-off line:

    Signed-off-by: Your Name <you@example.com>

`git commit -s` adds it for you. By signing off, you certify that you wrote the change or have the right to submit it under this repository's license.

## Names and logos

Contributions are under the repository's license. That license does not cover Modern AI names or logos. See TRADEMARKS.md.
