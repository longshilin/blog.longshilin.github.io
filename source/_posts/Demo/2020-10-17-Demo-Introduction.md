---
title: longsl-website-custom-module Demo Introduction
---

# Base

- Git clone this Repo.
- Replace `longsl-website-custom-module` to `YOUR-MODULE-NAME`.
- Create a empty branch `gh-pages` for the website.

# Advance

if you want change the default theme, then 
- edit the base _config.yml and change theme config to what you want.
- use the follow script to add the theme to `.gitmodules` files, like `[submodule "themes/next"]`

```shell script
git submodule add https://github.com/theme-next/hexo-theme-next.git themes/next
```
