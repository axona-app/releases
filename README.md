<p align="center">
  <img src="assets/logo.svg" width="88" alt="Axona">
</p>

<h1 align="center">Axona</h1>

<p align="center">
  Agent-aware knowledge workstation.<br>
  Your knowledge stops being an archive — signal moves between ideas.
</p>

---

Your notes outgrew the place you keep them. Folders flatten the connections. A wiki holds links but not the structure beneath them. And the parts you never wrote down still live in your head, where search can't reach.

Axona is a desktop app built for that gap. It reads a folder of plain-text notes. One shortcut captures a thought over any app; another opens search across the whole folder. Each note shows its links and backlinks. A typed graph, where a definition and an index term are their own kinds of link, is in development.

If you've kept notes in folders, a wiki, or a graph-style notes app, you know the shape of the problem. Axona differs in three ways: capture and search work from any app, your files stay plain text on your own disk, and the links between notes are kept, not flattened into folders. It's trying to beat keeping it all in your head.

## Download

**Axona 0.1.1**, for macOS (Apple Silicon and Intel). The first public build came out in July; this one fixes indexing. Early, so expect rough edges.

- **[Download the latest release](https://github.com/axona-app/releases/releases/latest)** — grab the `.dmg`.
- What's here today: a capture overlay and a search overlay you can open from any app, full-text search, a reader with links and backlinks, and local indexing of a plain-text folder. The typed graph and agents are in development.

Global shortcuts: **⌃⌥Space** search · **⌃⌥N** quick note · **⌃⌥A** show the window.

- **[Discussions](https://github.com/axona-app/releases/discussions)** — ideas and feedback.
- **[Issues](https://github.com/axona-app/releases/issues)** — bugs and requests.

## Why local-first

Your knowledge base is a folder of text files on your own disk. If Axona ever disappears, your notes still open in any editor. The search index is just a cache Axona rebuilds; your notes never live in a database, and there's nothing to export if you leave.

## Formats

Axona reads and writes plain-text notes: **Markdown** and **Podlite**. An existing Markdown folder opens directly; Podlite, a structured plain-text format, adds the typed links and definitions Markdown can't express.

## License

Axona is proprietary. The formats underneath it are open, and your files are always yours. A plugin API and developer docs become public when the extension surface is ready.

See the [License & Terms](LICENSE.md) and the [Privacy note](PRIVACY.md).
