# Repository Instructions

- Write JSON, TOML, Markdown, and JavaScript files as UTF-8 without BOM.
- Do not use Windows PowerShell defaults that can emit UTF-16 or UTF-8 with BOM when creating JSON files.
- For PowerShell writes that must preserve strict JSON parser compatibility, use [System.Text.UTF8Encoding]::new($false).
