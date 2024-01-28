# Glow.yazi

Plugin for yazi to preview markdown files with glow. To install, clone the repo inside your `.config/yazi/plugins/` folder and change your `yazi.toml` settings adding:

```toml
[plugin]
prepend_previewers = [
  { name = "*.md", exec = "glow" },
]
```

Make sure to have glow installed on your machine and added in PATH
