# Non-Convex Labs

OSS-first AI infrastructure. Engineering shop run by [Aaddrick Williams](https://github.com/aaddrick).

We ship Claude Code agents, MCP servers, and Laravel packages, then write up what we learned. The shop also takes on consulting and training work, but the open source is the front door. The name is a nod to non-convex optimization: the hard problems where local minima look like solutions and aren't. Most of the interesting work in AI tooling lives in that shape.

## Open source

Projects from the shop and from the founder's personal account, all in the same problem space.

- **[laravel-commonplace](https://github.com/non-convex-labs/laravel-commonplace)**: A database-backed personal knowledge vault for Laravel. Wikilinks, version history, semantic search, and an MCP server so Claude Code, Cursor, and Zed can read and write notes under your app's auth. Same database, same backup, no second silo.
- **[claude-desktop-debian](https://github.com/aaddrick/claude-desktop-debian)**: Claude Desktop for Linux. Repackages the Windows Electron build into `.deb`, `.rpm`, AppImage, AUR, and a Nix flake. Around 3,500 downloads/day. Exists because Anthropic hasn't shipped official Linux support. Maintained with collaborators outside the shop.
- **[claude-pipeline](https://github.com/aaddrick/claude-pipeline)**: Portable Claude Code multi-agent pipeline. Skills, agents, hooks, orchestration scripts, quality gates. The same pipeline that ships features to nonconvexlabs.com.
- **[claude-desktop-versions](https://github.com/aaddrick/claude-desktop-versions)**: The release-notes pipeline behind every claude-desktop-debian release. Diffs the minified Electron build, deobfuscates with Sonnet, ships a real changelog.
- **[written-voice-replication](https://github.com/aaddrick/written-voice-replication)**: A Claude Code pipeline that analyzes a text corpus and produces voice-replication prompts. Powers the "Can You Quantify a Writing Voice?" post.
- **[contrarian](https://github.com/aaddrick/contrarian)**: Devil's advocate analyst agent for Claude Code. Stress-tests proposals by challenging assumptions before you commit to them.

## Long-form writing

The blog is where the OSS work gets explained.

- [Can You Quantify a Writing Voice?](https://nonconvexlabs.com/blog/can-you-quantify-a-writing-voice): Building a pipeline that measures a writer's voice along enough axes that another model can produce drafts in it.
- [Building a Knowledge Base That Speaks to Both Humans and AI](https://nonconvexlabs.com/blog/building-a-knowledge-base-that-speaks-to-both-humans-and-ai): The design behind laravel-commonplace. One data store, one schema, two interfaces.
- [OSS Maintainers Can Inject Their Standards Into Contributors' AI Tools](https://nonconvexlabs.com/blog/oss-maintainers-can-inject-their-standards-into-contributors-ai-tools): CLAUDE.md and AGENTS.md as infrastructure. Your conventions are in the room before the contributor opens a PR.

More at [nonconvexlabs.com/blog](https://nonconvexlabs.com/blog).

## Work with us

We take on engineering work in agentic systems, MCP, and AI training for teams that want to ship rather than prototype. If that's you, reach out at [nonconvexlabs.com/contact](https://nonconvexlabs.com/contact).

---
Aaddrick Williams · [nonconvexlabs.com](https://nonconvexlabs.com) · [blog](https://nonconvexlabs.com/blog)
