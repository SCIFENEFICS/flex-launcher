# Flex Launcher
## Project Helios Edition

A lightweight, controller-friendly application launcher customised for Project Helios.

---

<img width="1296" height="816" alt="image" src="https://github.com/user-attachments/assets/8b3c0af4-d9f9-44ed-a141-f5cdbd0e5eea" />



---

## Looking for the Original Flex Launcher?

This repository documents the **Project Helios edition** of Flex Launcher and the changes developed specifically for Helios.

For complete information about the original project, including screenshots, supported platforms, installation instructions, controls and general documentation, visit the upstream repository created by **ComplexLogic**:

**[Original Flex Launcher repository](https://github.com/complexlogic/flex-launcher)**

Project Helios would not exist in its current form without the excellent foundation provided by ComplexLogic and the original Flex Launcher contributors.

---

## About This Fork

Project Helios required additional layout, navigation and clock configuration options for a clean, controller-driven media interface.

This fork keeps those Helios-specific changes together while remaining as compatible with the upstream project as practical.

## Helios Features

### Launcher

- Rounded selection highlight.
- Improved highlight rendering.
- Configurable multi-row launcher layouts.
- Configurable maximum number of launcher icons.
- Configurable icon spacing.
- Configurable row spacing.
- Configurable interface logo with PNG and SVG support.
- Configurable icon drop shadows (colour, opacity, blur and offset).
- Improved keyboard navigation.
- Improved controller navigation.
- Improved page navigation that preserves the selected row when moving between pages.

### Clock

- Independent clock and date font sizing.
- Configurable clock positioning.
- Easier clock sizing and styling.

### Configuration

Additional Helios options are configured through `config.ini`.

```ini
[Layout]
MaxButtons=8
Rows=2
RowSpacing=40
IconSpacing=6%

IconShadows=true
IconShadowColor=#000000
IconShadowOpacity=20%
IconShadowBlur=12

[Logo]
LogoEnabled=true
LogoImage=/usr/share/helios/icons/helios-white.svg
LogoAlignment=Left
LogoMargin=12
LogoWidth=110

[Clock]
ClockDateFontSize=36
```

Existing Flex Launcher configuration remains supported where practical.

---

## Installation and Documentation

This README intentionally focuses on the Project Helios changes rather than duplicating the original Flex Launcher documentation.

For installation instructions, platform support, usage information, controls and build guidance, visit:

**[Flex Launcher documentation](https://github.com/complexlogic/flex-launcher)**

## Project Helios

Project Helios is a lightweight, Debian-based media operating system designed to replace slow, ad-filled smart TV software with a fast, simple and controller-friendly experience.

It is built primarily for Plex users while also supporting game streaming, ad-free YouTube, music streaming, local media playback and other carefully selected applications.

**[Visit the Project Helios repository](https://github.com/SCIFENEFICS/project-helios)**

## Development

This fork is developed primarily for Project Helios. Development has made extensive use of AI-assisted software development alongside manual design, testing, debugging and validation.

## License

This fork retains the licensing terms of the original Flex Launcher project. See the repository's license file for details.

## Disclaimer

This is a personal project provided **as-is**, without any warranty or guarantee of support. Use it entirely at your own risk.

Constructive feedback and bug reports are welcome. However, support, troubleshooting, feature requests and fixes cannot be guaranteed.
