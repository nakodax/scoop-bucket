# NakodaX Scoop bucket

Install [NakodaX](https://nakodax.com) command-line tools on Windows with [Scoop](https://scoop.sh).

Scoop installs apps from lists called buckets. This bucket is NakodaX's list: it tells Scoop where to download each tool and how to check it. Add it once, and Scoop can install and update NakodaX tools like any other app.

## Install

```powershell
scoop bucket add nakodax https://github.com/nakodax/scoop-bucket
scoop install nakodax/nkx-upload
```

Update with `scoop update nkx-upload`, and remove it with `scoop uninstall nkx-upload`.

## Tools in this bucket

| Tool | What it does |
|---|---|
| [nkx-upload](https://github.com/nakodax/nkx-upload) | Encrypts large video and audio recordings (up to 5 GB) on your computer and uploads them to [NakodaX box](https://box.nakodax.com) |

No Scoop? Install nkx-upload in PowerShell instead:

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://box.nakodax.com/install.ps1 | iex"
```

## About NakodaX

NakodaX helps you keep control of sensitive work after you share it. It protects documents, media, data and software with encryption and permission checks at the point of use, so you can change, limit or revoke access at any time.

- [nakodax.com](https://nakodax.com)
- [Document protection](https://nakodax.com/documents)
- [Support](https://nakodax.com/support)

Each manifest in `bucket/` is updated with every release.
