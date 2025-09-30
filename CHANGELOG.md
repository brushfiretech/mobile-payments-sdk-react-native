## Changelog

### v2025.9.30 Sep 30, 2025

- **Improved**: Updated TypeScript types to use primitive types (`string`, `boolean`, `number`) instead of constructor types (`String`, `Boolean`, `Number`) for better type checking and IDE support
- iOS: Updated native SDK to version 2.3
- Android: Added support for additional `ReaderUnavailableReason` values
- Updated `PaymentParametersError` handling
- Fixed iOS build configuration to ensure proper script phase ordering
- General synchronization with Square SDK updates

### v2025.2.1 Feb 19, 2025

- Address NPM dependency issue

### v2025.2.0 Feb 19, 2025

- iOS:
  - Fixed an issue with the `MockReaderUI` dependency for release build configurations.
  - Bump native SDK version to 2.0.2.

### v2025.1.0 Jan 23, 2025

- Released the Mobile Payments SDK React Native plugin.
