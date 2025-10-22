![Midnight](https://raw.githubusercontent.com/Serendipity-Theme/assets/main/githubHeader.png)

# Serendipity for Ghostty

Relaxed, gentle and modern color themes for [Ghostty](https://ghostty.org) terminal.

## Available Themes

- **Serendipity Morning** - Light theme with soft, gentle colors
- **Serendipity Sunset** - Dark theme with warm tones
- **Serendipity Midnight** - Dark theme with cool tones
- **Serendipity Midnight Minimal** - Minimal dark theme

# Installation

### Option 1: Manual Installation

1. Copy the theme files from the `themes/` directory to your Ghostty themes folder:

   ```bash
   cp themes/serendipity-* ~/.config/ghostty/themes/
   ```

2. Edit your Ghostty config file (`~/.config/ghostty/config`) and add one of the following:

   **Single theme:**

   ```
   theme = serendipity-midnight
   ```

   **Auto-switch between light and dark based on system appearance:**

   ```
   theme = "light:serendipity-morning,dark:serendipity-midnight"
   ```

3. Restart Ghostty or open a new window to apply the theme.

### Option 2: Clone Repository

```bash
git clone https://github.com/flaticols/Serendipity-Theme-Ghostty.git
cd Serendipity-Theme-Ghostty
cp themes/serendipity-* ~/.config/ghostty/themes/
```

Then follow step 2 above to configure your theme.

## Verify Installation

You can verify the themes are installed correctly by running:

```bash
ghostty +list-themes | grep serendipity
```

# Screenshots Under this heading

# Who ported the theme?

Ported by [flaticols](https://github.com/flaticols) from the original [Serendipity Theme for Zed](https://github.com/meocoder31099/Serendipity-Theme-Zed).

# Standard formatting

- Add the same header on the repo
- Call the repo as the app you are porting for.
