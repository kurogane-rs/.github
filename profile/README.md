<p align="center">
  <img alt="Kurogane. Chromium, on your terms." src="https://github.com/kurogane-rs/.github/raw/master/profile/banner.png" width="100%">
</p>

Build high-performance, GPU-accelerated desktop applications or embed Chromium directly into existing applications.

Kurogane is a Rust-native runtime built on [Chromium Embedded Framework (CEF)](https://en.wikipedia.org/wiki/Chromium_Embedded_Framework) bringing Chromium to desktop applications while giving you control over windowing, event loops and lifecycle when you need it.

See the [website](https://kurogane-rs.org) for benchmarks and comparisons.

## Get started

Install the CLI on Linux and macOS:

```bash
curl --proto '=https' --tlsv1.2 -LsSf https://kurogane-rs.org/install.sh | sh
```

Install it on Windows:

```powershell
powershell -c "irm https://kurogane-rs.org/install.ps1|iex"
```

See it run:

```bash
kurogane showcase
```

## Projects

| Project | What it is |
|---|---|
| [kurogane](https://github.com/0x48piraj/kurogane) | The runtime and its CLI |
| [tanso](https://github.com/kurogane-rs/tanso) | Rust bindings to the Chromium Embedded Framework |
| [kurogane-install](https://github.com/kurogane-rs/kurogane-install) | The CLI's installers and release pipeline |
| [kurogane-showcase](https://github.com/kurogane-rs/kurogane-showcase) | A wgpu galaxy and three live Chromium panes in one winit loop |
| [kurogane-shell](https://github.com/kurogane-rs/kurogane-shell) | The Rust shell Kurogane adds to an existing frontend project |

## Starters

`kurogane new` creates a project from a starter.

| Starter | What it is |
|---|---|
| [minimal](https://github.com/kurogane-rs/kurogane-starter-minimal) | HTML, CSS and TypeScript or JavaScript with no framework |
| [react](https://github.com/kurogane-rs/kurogane-starter-react) | React with Vite |
| [svelte](https://github.com/kurogane-rs/kurogane-starter-svelte) | Svelte 5 with Vite |
| [vue](https://github.com/kurogane-rs/kurogane-starter-vue) | Vue 3 with Vite |
