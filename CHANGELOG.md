# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-02-13

### Added - join-old Integration

- 16 Profile Badge Colors (--badge-1 to --badge-16)
- Task Category Colors (--task-user-story, --task-technical)
- Priority Colors (--priority-urgent, --priority-high, --priority-medium, --priority-low)
- Button State Variables (--button-primary-_, --button-secondary-_, --button-disabled-\*)
- Toast Component Mixins (toast-container, toast-base, toast-success, toast-error, toast-warning, toast-info)
- Progress Bar Mixins (progress-bar, progress-bar-rounded)
- Badge Mixins (badge, priority-badge, task-badge)
- Component-specific tokens (--toast-_, --progress-_)
- Dark Mode variants for all new colors
- New file: `abstracts/_mixins-components.scss`
- Documentation: FEATURES-JOIN-OLD.md

### Changed

- Updated all import paths in Minecraft project
- Extended CSS Custom Properties with 40+ new variables
- Version bump to 1.1.0

## [1.0.0] - 2026-02-13

### Added

- Initial release of @dev2k/scss-library
- CSS Custom Properties system with comprehensive design tokens
- Responsive breakpoint mixins (mobile-landscape, tablet, laptop, desktop, etc.)
- Flexbox mixins (flex-center, flex-between, flex-column, etc.)
- Layout mixins (container, grid-auto-fit, aspect-ratio, etc.)
- Typography mixins (heading-1 to heading-6, body, subtitle, etc.)
- Button mixins (button-primary, button-outline, button-icon, etc.)
- Utility mixins (transition, focus-ring, custom-scrollbar, etc.)
- Modern CSS reset based on modern-normalize
- Base typography styles with utility classes
- Optional utility helper classes
- Dark mode support with automatic color switching
- JSDoc documentation for all mixins
- Comprehensive README with usage examples
- NPM package.json configuration
- MIT License

### Structure

- `/abstracts` - Variables and mixins
- `/base` - Reset and typography
- `/utils` - Optional utility classes
- Main entry point `_index.scss`

### Design Tokens

- Spacing system (0-32 with rem units)
- Color system (grays, semantic colors, theme colors)
- Typography scale (xs to 5xl with responsive clamp)
- Border radius system (xs to full)
- Shadow system (xs to 2xl)
- Transition timing functions
- Z-index layers

[1.0.0]: https://github.com/dev2k/scss-library/releases/tag/v1.0.0
