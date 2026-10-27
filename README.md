# Corbelo plugins

An opinionated foundation and human-designed product features for your AI to
build on. Software for your business, your next idea, or yourself.

[Get started](https://corbelo.dev/build-with-ai/) ·
[Explore features](https://corbelo.dev/catalog/) ·
[Free foundation](https://corbelo.dev/foundation/) ·
[Local setup](https://corbelo.dev/docs/keys/)

## ChatGPT

Open **Plugins → Add custom MCP server**, use
`https://corbelo.dev/corbelo/mcp`, name it **Corbelo**, and select **None** for
authentication. Start a new chat and ask ChatGPT to use Corbelo to explore your
idea. Account and workspace policies may limit custom connections.

The direct connection provides public catalog tools. It does not automatically
install the bundled workflows. The [OpenAI package](openai/) includes those
workflows for compatible plugin installations and directory submission. Public
directory publication is a separate review; no directory listing is claimed.

## Claude

Download the [Claude plugin](https://corbelo.dev/integrations/corbelo-claude-1.0.0.zip).
In **Customize → Plugins**, upload the ZIP. Claude plugins currently require a
paid Claude plan; workspace policies may restrict installation.

Alternatively, add the same public URL in **Customize → Connectors** with no
authentication. That gives catalog tools without the packaged workflows.

## Claude Code

In a current Claude Code session:

```text
/plugin install corbelo --marketplace kylebegeman/corbelo-plugins
```

For older clients, add the marketplace first, then install:

```text
/plugin marketplace add kylebegeman/corbelo-plugins
/plugin install corbelo@corbelo
```

## Codex

```sh
codex plugin marketplace add kylebegeman/corbelo-plugins
codex plugin add corbelo@corbelo
```

Start a new session after installing. The marketplace contains the [OpenAI
package](openai/) with the same three workflows as the Claude package.

## Try a small idea

> Use Corbelo to help me plan a small app for tracking equipment I lend to
> friends. Start with the simplest useful version. Explain what I get, what I
> need to build, and where I would run it. Do not change any files yet.

- **corbelo-discover:** explore the fit and choose a starting point.
- **corbelo-build:** plan, integrate and verify in a supported coding workspace.
- **corbelo-extend:** review additions or updates to an existing product.

The public connection reads current catalog information. It does not upload your
repository, access your account, install code or provide hosting. Building needs
a coding workspace and Corbelo’s separately installed CLI or local MCP tools.
The free foundation is the evaluation path. Paid feature source uses existing
Pro access checks. Never paste a key into chat. During coming-soon mode,
payments remain disabled and a reservation does not grant Pro source access.

## Packages and privacy

The [package metadata](releases.json) lists versioned archives and SHA-256
checksums. Both platform packages are generated from shared workflows; changes
are reviewed together. This public repository contains only the plugin packages
and distribution metadata. It contains no Engine or service implementation.

[Privacy](https://corbelo.dev/privacy/) ·
[Support](mailto:hello@corbelo.dev) ·
[Source license for installed product features](https://corbelo.dev/license/)

Plugin files are MIT licensed. Corbelo feature source has its own license.
