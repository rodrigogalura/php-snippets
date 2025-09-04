# PHP Snippets for Sublime Text

A complete snippet collection for **PHP 7.0 → 8.3** features.

## 🚀 Features
- Covers new PHP features from 7.0 up to 8.3
- Organized by version (`PHP7/`, `PHP8/`)
- Easy tab triggers for quick coding

## ⚡ Usage
1. Clone or copy this repo into your Sublime `Packages` folder.
   - Windows: `%APPDATA%\Sublime Text\Packages`
   - macOS: `~/Library/Application Support/Sublime Text/Packages`
   - Linux: `~/.config/sublime-text/Packages`
2. Type the **tab trigger** (e.g. `fn`, `match`, `readonly`) in a PHP file and press `Tab`.

## ✅ Example
Typing `match` then pressing `Tab` expands into:

```php
$result = match($statusCode) {
    200 => 'OK',
    404 => 'Not Found',
    500 => 'Server Error',
    default => 'Unknown',
};
