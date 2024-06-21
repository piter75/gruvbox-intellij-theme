<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# Gruvbox theme changelog

## 0.7.3
- Don't use bright colors in console - IntelliJ's terminal already uses bold font
- Fix Groovy keyword colors in dark soft and medium themes
- Adjust memory indicator colors for dark soft and medium themes
- Adjust run widget colors for dark soft and medium themes

## 0.7.2
- Fix unfocused selection foreground in unfocused VCS Log

## 0.7.1

- Add preliminary versions of Gruvbox Material Dark Medium and Soft variants
- Fix completion popup background in Dark Medium variant

## 0.7.0
- adjusted Dark Medium and Dark Soft variants to better adhere to original Gruvbox theme

## 0.6.9

### Added
- 2023.3+ support
- removed `untilBuild` since there's rarely any breaking changes for theme only extensions

## 0.6.8

### Changed
- remove explicit foreground color for language injections so the syntaxhighlighting works

## 0.6.6

### Added
- 2023.1 support

### Fix
- build system

## 0.6.5

### Added
- 2022.3 support

## 0.5.5

### Added
- 2022.2 support (thanks @gpopides)

## 0.5.4

### Added
- 2022.1 support (thanks @fabianhjr)

## 0.5.3

### Added
- 2021.3 support

### Changed
- The wrap guide color is now the same as the indent guide color
- Attempt to fix go syntax highlighting (thanks @ravron)

## 0.5.2

### Added
- 2021.2 support

## 0.5.1

### Changed
- Fixed `pluginSinceBuild`

## 0.5.0

### Changed
- Update Gradle build to https://github.com/JetBrains/intellij-platform-plugin-template
- The changelog is now a markdown file instead of hardcoded HTML
- Predefined symbol's foreground is now the same as constants
- Function/method calls now have the default foreground
- Errors/deprecations no longer have a red foreground, just a red wave to avoid confusion with keywords
- Add scrollbar colors

## 0.4.4

### Added
- 2021.1 support (thanks @tomaszkaliciak)

## 0.4.3

### Added
- 2020.3 support (thanks @hravnx)

### Fixed
- Fix background color of the first item from the autocomplete list
- Fix breakpoint background in Light themes
- Fix file highlight in Dark Soft theme

## 0.4.2

### Fixed
- Fix PyCharm Python Console prompt. (thanks @lemontheme)

## 0.4.1

### Added
- 2020.2 support (thanks @jef)

## 0.4.0

### Added
- Add light variants (thanks @mariushelf)

### Fixed
- Fix ANSI black color in the console
- Fix completion popup background

## 0.3.1

### Fixed
- Fix Dark Hard variant: Selected background is now darker than the background

## 0.3.0

### Added
- 2020.0 support (thanks @camsteffen)
- Add Dark Hard and Dark Soft variants

### Changed
- Remove default font in the color scheme so that users keep their font settings

### Fixed
- Fix selection inactive background color. (thanks @rkashapov)

## 0.2.1

### Added
- Android Studio 3.4.2 and IDEA 2018.3 support

## 0.2.0

### Added
- Add opacity to various colors

## 0.1.3

### Added
- Add compatibility for newer versions and an icon

## 0.1.2

### Changed
- There is a different color when a file is selected in the project pane but is not focused

## 0.1.1

### Changed
- The button to close the editor tabs is now brighter

## 0.1.0

### Added
- Initial release
