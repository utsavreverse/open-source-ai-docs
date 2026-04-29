---
icon: lucide/arrow-down-to-line
---

# Installation

OpenCode has a terminal interface, a desktop version, and extensions for different IDEs, although it is recommended to use the **terminal** version as it is more optimized than the other versions

### Desktop Installation (Beta Version)

Download directly from their [website](https://opencode.ai/download) according to your operating system.

### Terminal Version (TUI) Installation

For the terminal version, if you use Linux or MacOS then it is pretty straightforward, but in case you use Windows, you need to have `npm` or `bun`.

=== ":fontawesome-brands-windows: Windows"
    Run this command for `npm`

    ```powershell
    npm i -g opencode-ai
    ```

    Run this command for `bun`

    ```powershell
    bun add -g opencode-ai
    ```

=== ":material-linux: Linux"
    Run this command on your terminal

    ```bash
    curl -fsSL https://opencode.ai/install | bash
    ```

=== ":material-apple: macOS"
    Run this command on your terminal

    ```bash
    curl -fsSL https://opencode.ai/install | bash
    ```

After successful installation run this to open OpenCode

```bash
opencode
```

<hr>

### Video Reference for Windows TUI Installation (using `npm`)

<video width="100%" controls>
  <source src="../assets/opencode-tui-install.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
