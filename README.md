# KickStart.css

A lightweight, utility-first CSS framework built with modern Sass (1.87.0). KickStart.css provides a comprehensive set of utility classes for rapid UI development.

## Features

- **Flexbox Utilities**: Comprehensive flexbox layout system
- **Responsive Design**: Built-in responsive breakpoints
- **Spacing System**: Margin and padding utilities
- **Sizing**: Height and width utilities
- **Colors**: Extensive named color system
- **Typography**: Text alignment and styling
- **Containers**: Responsive container system
- **Miscellaneous**: Additional utility classes

## Installation

### Using Deno

```bash
deno run -A npm:sass ./src/kickstart.scss ./kickstart.css
```

### Using npm

```bash
npm install kickstart.css
```

## Usage

Include the compiled CSS in your HTML:

```html
<link rel="stylesheet" href="path/to/kickstart.css">
```

## Utility Classes

### Flexbox

```html
<div class="flex-row justify-center align-center">
  <!-- Content -->
</div>
```

### Spacing

```html
<div class="m-1 p-2">
  <!-- Content -->
</div>
```

### Sizing

```html
<div class="w-50 h-50v">
  <!-- Content -->
</div>
```

### Colors

```html
<div class="bg-aliceblue txt-darkblue">
  <!-- Content -->
</div>
```

### Text

```html
<p class="txt-center">
  Centered text
</p>
```

## Breakpoints

KickStart.css includes 7 responsive breakpoints:

- `xxs`: 0px
- `xs`: 368px
- `s`: 576px
- `m`: 768px
- `l`: 992px
- `xl`: 1200px
- `xxl`: 1400px

## Development

### Prerequisites

- Deno
- Sass 1.87.0

### Building

```bash
# Compile CSS
deno task compile

# Watch for changes
deno task watch
```

## Project Structure

```
src/
├── _variables.scss        # Global variables
├── _screen_breakpoints.scss # Responsive breakpoints
├── _containers.scss       # Container system
├── _flex_box.scss         # Flexbox utilities
├── _height_and_width.scss # Sizing utilities
├── _margin_and_padding.scss # Spacing utilities
├── _named_colors.scss     # Color system
├── _text.scss            # Typography utilities
├── _misc.scss            # Miscellaneous utilities
└── kickstart.scss        # Main entry point
```

## License

MIT License - See [LICENSE](LICENSE) file for details

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Author

PatMan10

## Version

Current version: 4.0.0
