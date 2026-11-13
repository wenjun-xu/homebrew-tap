# TokenFlow Homebrew Tap

Homebrew installation source for the local, read-only GitHub Copilot CLI token usage dashboard.

```bash
brew install wenjun-xu/tap/tokenflow
tokenflow start
```

The v0.2.3 prerelease provides standalone executables for each Mac architecture.
No Python, Node.js, Bun, or compilation is required on the user's machine.
This version provides an English interface and documentation, improved date filtering,
all-session usage bars ordered like the session list, and bounded scrollable detail lists
with visible blue chart gradients. The homepage refreshes every 15 seconds, preserving
filter drafts, pagination, and scroll positions; refresh pauses in the background and during interaction.

Upgrade an existing installation:

```bash
tokenflow stop
brew update
brew upgrade wenjun-xu/tap/tokenflow
tokenflow --version
tokenflow start
```

Run `tokenflow stop` before upgrading or uninstalling. Requires macOS 14 or later
and verifiable sandbox-exec file-write isolation.
Apple Silicon and x64 executables under Rosetta have been checked with synthetic data;
native Intel Macs and other macOS versions still await acceptance.
Real sessions, databases, and logs are never uploaded. GitHub downloads remain subject
to internal-network and proxy policies; this project does not provide an internal mirror.

Source code, full documentation, and releases:
[wenjun-xu/TokenFlow](https://github.com/wenjun-xu/TokenFlow).
