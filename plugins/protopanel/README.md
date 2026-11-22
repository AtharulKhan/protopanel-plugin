# ProtoPanel for Claude Code and Codex

Install this public plug-in to connect your own ProtoPanel account through MCP. An external agent can read the projects you authorize, upload images, build drafts and request your review. Your ProtoPanel account controls access and publication.

## Claude Code

Run these commands in your terminal.

```sh
claude plugin marketplace add AtharulKhan/protopanel-plugin
claude plugin install protopanel@protopanel-plugins
```

Start a new Claude Code session. Open `/mcp`, select the ProtoPanel server and choose Authenticate. Review the permissions and allow the connection in ProtoPanel.

## Codex

```sh
codex plugin marketplace add AtharulKhan/protopanel-plugin
codex plugin add protopanel@protopanel-plugins
codex mcp login protopanel
```

Complete the browser authorization and start a new session. Try “List my ProtoPanel projects.” An empty list is a successful connection for a new account.

You can disconnect a client at any time under **MCP access** in ProtoPanel. The [setup page](https://protopanel.vercel.app/plugins) also includes direct MCP setup for other clients and a ZIP download.
