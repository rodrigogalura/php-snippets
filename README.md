# 📦 PHP-Snippets for Sublime Text

A collection of **ready-to-use Sublime Text snippets** for modern PHP (7.0 → 8.3).
Easily insert the latest PHP features with **Tab triggers** or the **Command Palette**.

✅ Organized per PHP version (70, 71, 72, …, 83)
✅ Covers major language features and syntax improvements
✅ Speeds up coding with autocompletion & boilerplate generation
✅ Includes `Default.sublime-commands` for Command Palette access

---

## 🚀 Features by PHP Version

- **7.0** → Scalar type hints, return types, null coalesce, spaceship operator, anonymous classes
- **7.1** → Nullable types, void return type, constant visibility
- **7.2** → `object` typehint, trailing commas in arrays
- **7.3** → Flexible heredoc/nowdoc, trailing commas in function calls
- **7.4** → Typed properties, arrow functions, null coalesce assignment, spread operator in arrays
- **8.0** → Match expression, constructor property promotion, nullsafe operator
- **8.1** → Enums, readonly properties, first-class callables
- **8.2** → Readonly classes, DNF types, `true|false|null` types
- **8.3** → Typed class constants, `json_validate()`, dynamic class constant fetch

---

## 📖 Usage

1. Install by copying `PHP-Snippets` into your Sublime `Packages` directory:
   - **Windows** → `%APPDATA%\Sublime Text\Packages\`
   - **macOS** → `~/Library/Application Support/Sublime Text/Packages/`
   - **Linux** → `~/.config/sublime-text/Packages/`

2. In a `.php` file:
   - Type the **tab trigger** (`fn`, `match`, `enum`, etc.) → press `Tab`
   - Or open **Command Palette** → search `PHP [version]: [snippet]`

---

## 🛠 Example

Typing `match` + **Tab** expands into:

```php
$result = match($value) {
    1 => 'one',
    2 => 'two',
    default => 'other',
};
```

⚡ Make PHP development faster, cleaner, and future-proof inside Sublime Text.
