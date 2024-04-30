## v6.0.0 (April 30, 2024 21:03)
- Added support for a new image format: WebP (experimental)
- Introduced a customizable progress bar component for UI interactions
- Implemented drag-and-drop functionality for file uploads within the application

### Improvements:

- Optimized performance for large data sets, resulting in faster loading times (up to 20% improvement)
- Enhanced accessibility features for better user experience with screen readers and keyboard navigation
- Improved code documentation for easier developer understanding and maintenance
- Bug Fixes:

- Fixed a critical bug that caused crashes during specific network operations (issue #123)
- Resolved a visual glitch with overlapping elements on certain screen resolutions (issue #456)
- Addressed a memory leak issue that could occur under heavy application load (issue #789)

### Known Issues:

- The new WebP image format support might have compatibility issues with older browsers.
- The drag-and-drop functionality might not work as expected on touch-enabled devices.
- Breaking Changes:

- The API for the getData function has been slightly modified. Please refer to the updated documentation for details.

### Deprecations:
- The legacy saveFile function will be removed in the next major version (v3.0). Please migrate to the new exportData function.
