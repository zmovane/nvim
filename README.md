
# nvim

A neovim configuration that integrates [avante.nvim](https://github.com/yetone/avante.nvim), allowing the use of multiple LLM models for coding.

<p align="center">
  <img src="./screenshot/screenshot.png" alt="Screenshot" />
</p>

## Importants

### Font

[Install nerd-fonts]("https://github.com/ryanoasis/nerd-fonts")

### Keymaps

#### General

| Key              | Description                   | Mode                |
| ------           | ---                           | ---                 |
| H                | To the first char of the line | **n**, **v**        |
| L                | To the end of the line        | **n**, **v**        |
| jj               | Exit insert mode              | **i**               |
| &lt;Up&gt;       | Increase window height        | **n**               |
| &lt;Down&gt;     | Decrease window height        | **n**               |
| &lt;Left&gt;     | Decrease window width         | **n**               |
| &lt;Right&gt;    | Increase window width         | **n**               |
| &lt;C-h&gt;      | Go to left window             | **n**               |
| &lt;C-j&gt;      | Go to lower window            | **n**               |
| &lt;C-k&gt;      | Go to upper window            | **n**               |
| &lt;C-l&gt;      | Go to right window            | **n**               |
| &lt;M-j&gt;      | Move down                     | **n**, **i**, **v** |
| &lt;M-k&gt;      | Move up                       | **n**, **i**, **v** |
| &lt;leader&gt;w  | Save file                     | **n**               |
| &lt;leader&gt;W  | Save files                    | **n**               |
| &lt;leader&gt;q  | Quit                          | **n**               |
| &lt;leader&gt;Q  | Force quit                    | **n**               |
| &lt;leader&gt;_  | Split below                   | **n**               |
| &lt;leader&gt;\| | Split right                   | **n**               |

#### Git

| Key              | Description           | Mode           |
| --------------   | --------------        | -------------- |
| leadergg         | Open lazy-git         | **n,v**        |

#### LSP

| Key              | Description           | Mode           |
| --------------   | --------------        | -------------- |
| gd               | Goto Definition       | **n**          |
| gD               | Goto Declaration      | **n**          |
| gr               | References            | **n**          |
| gi               | Goto Implementation   | **n**          |
| gt               | Goto Type Definition  | **n**          |
| K                | Hover                 | **n**          |
| gK               | Signature Help        | **n**          |
| &lt;C-k&gt;      | Signature Help        | **i**          |
| [d               | Next Diagnostic       | **n**          |
| ]d               | Prev Diagnostic       | **n**          |
| &lt;leader&gt;ca | Code Action           | **n**          |
| &lt;leader&gt;cr | Rename                | **n**          |
| &lt;leader&gt;cf | Format Document/Range | **n**, **v**   |
| &lt;leader&gt;ll | Lsp log               | **n**          |
| &lt;leader&gt;li | Lsp info              | **n**          |
| &lt;leader&gt;lr | Lsp restart           | **n**          |

