<p align="center">
  <img src="assets/logo.svg" width="88" alt="Axona">
</p>

<h1 align="center">Axona</h1>

<p align="center">
  Agent-aware knowledge workstation.<br>
  Your knowledge stops being an archive — signal moves between ideas.
</p>

---

Axona is a desktop app for a folder of plain-text notes. From any app, **⌃⌥N** saves a quick note and **⌃⌥Space** searches the whole folder. Each note shows its links and backlinks. A typed graph, where a definition and an index term are separate kinds of link, is in development.

How it differs from folders, a wiki or a graph-style notes app:

- capture and search work from any app;
- the files stay plain text on your own disk;
- links between notes are kept rather than turned into folders.

## Download

**Axona 0.1.2** for macOS (Apple Silicon and Intel). This version adds a Recent notes window and saves your text as you type. Axona now waits for every window to save before it quits.

- **[Download the latest release](https://github.com/axona-app/releases/releases/latest)** and open the `.dmg`.
- Included today: a quick-note panel, search and Recent notes, all opened from any app; full-text search; a reader with links and backlinks; indexing of a local folder. The typed graph and agents are still in development.

Global shortcuts: **⌃⌥Space** search · **⌃⌥N** quick note · **⌃⌘R** recent notes · **⌃⌥A** show the window.

- **[Discussions](https://github.com/axona-app/releases/discussions)**: ideas and feedback.
- **[Issues](https://github.com/axona-app/releases/issues)**: bugs and requests.

## Why local-first

Your knowledge base is a folder of text files on your own disk, and any text editor can open it. The search index is a cache that Axona rebuilds when needed. Notes are never stored in a database, so there is nothing to export if you stop using Axona.

## Formats

Axona reads and writes **Markdown** and **Podlite** notes. An existing Markdown folder opens as is. Podlite is a structured plain-text format with typed links and definitions, which Markdown has no syntax for.

## License

Axona is proprietary. The file formats it uses are open, and your files belong to you. A plugin API and developer docs will be published once the extension interface is ready.

See the [License & Terms](LICENSE.md) and the [Privacy note](PRIVACY.md).
