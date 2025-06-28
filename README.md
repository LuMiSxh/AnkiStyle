# Modern Anki Card Styles for Japanese Learning

A collection of redesigned Anki card templates with a modern, minimalistic design system. This repository contains both the original default styles and custom redesigned versions for popular Japanese learning decks.

## Supported Card Types

- **JLAB** - Japanese Like a Breeze listening and cloze cards (both card types)
- **Genki Vocab** - Genki vocabulary cards
- **Genki Kanji** - Genki kanji cards with readings and meanings
- **Info Note** - Information display cards

## Key Features

- **Consistent Design Language** - Unified visual style across all card types
- **Mobile-Friendly** - Responsive design optimized for phones and tablets
- **Dark Mode Support** - Automatic theme switching based on Anki's night mode
- **Modern Typography** - Clean, readable fonts with proper Japanese character support
- **Improved Readability** - Better contrast and spacing for enhanced learning experience

## Installation

1. Open Anki and go to **Tools > Manage Note Types**
2. Select the note type you want to update
3. Click **Cards** to open the card template editor
4. Choose your preferred style version:
    - Use `default/` for original styling
    - Use `custom_1/` for modern minimalistic design
5. For each card template:
    - Copy the contents from `front.html` to the **Front Template**
    - Copy the contents from `back.html` to the **Back Template**
    - Copy the contents from `style.css` to the **Styling** section
6. Click **Close** to save changes

## Repository Structure

```
├── jlab/
│   ├── default/              # Original default styles
│   └── custom_1/             # Modern redesigned styles
├── genki-vocab/              # Genki vocabulary cards
│   ├── default/
│   └── custom_1/
├── genki-kanji/              # Genki kanji cards
│   ├── default/
│   └── custom_1/
└── info-note/                # Information display cards
    ├── default/
    └── custom_1/
```

Each template folder contains:
- `front.html` - Front side template
- `back.html` - Back side template
- `style.css` - Styling definitions

### Version Naming

- **default/** - Original card templates as provided by the deck creators
- **custom_1/** - First custom redesign with modern minimalistic styling
- Future versions may include `custom_2/`, `custom_3/`, etc. with different design approaches

## Design Philosophy

The custom styles follow modern minimalistic design principles:

- **Clean Interface** - Uncluttered layouts that focus attention on content
- **Responsive Typography** - Font sizes that scale appropriately across devices
- **Semantic Color System** - Consistent use of colors for different types of information
- **Accessibility First** - High contrast ratios and readable font choices

## Technical Details

- Uses CSS custom properties for consistent theming
- Supports both light and dark modes automatically
- Optimized for mobile viewing with responsive breakpoints
- Includes print-friendly styles
- Font stack prioritizes Japanese fonts followed by system fonts

## Requirements

- Anki 2.2+ (for proper CSS support)
- Compatible with AnkiMobile and AnkiDroid
- No additional add-ons required

## Before Using

Make sure to backup your existing card templates before applying these styles. You can export your deck or copy the current templates to a text file as a precaution.

## Contributing

Feel free to submit issues or pull requests if you find bugs or have suggestions for improvements.

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- JLAB (Japanese Like a Breeze) for the original listening and cloze card templates
- Genki textbook series for the vocabulary and kanji deck templates
- Anki community for inspiration and feedback