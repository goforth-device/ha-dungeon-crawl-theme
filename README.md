# Dungeon Crawl theme for Home Assistant

A loud, neon dungeon theme: torch-lit stone walls, dark cards, gold and magenta headings. All the art is original and drawn by script.

![Banner](images/banner.png)

## Install

1. In HACS, add this repository as a custom repository of type **Theme**, then download it.
2. Call the `frontend.reload_themes` action.
3. Pick **Dungeon Crawl** on a view under its **Theme** setting, or in your profile.

The theme's background image loads from this repository, so it needs internet access.

## Pictures

`images/` also holds a banner, a cat, a pair of heart boxers and a gold chest for use in picture or markdown cards.

## Fonts

The theme asks for Bungee and Share Tech Mono and falls back to system fonts. To load them, add this as a dashboard resource of type **Stylesheet**:

```
https://fonts.googleapis.com/css2?family=Bungee&family=Share+Tech+Mono&display=swap
```
