# Changelog

## **0.1.0 - Initial release**

- First page style.
- Level 1 headings chapter style.

## **0.1.1**

- Fixed major issue where custom school & company logos would throw an error.
- Added option to customize footer left side text (thus fixing the issue of it being hardcoded).

## **0.2.0**

- **Features**
  - Arabic language support. The template now supports Arabic, English and French.
  - New `lang` parameter to specify the language. Consequently, the `french` parameter that used to enabled French instead of English is now deprecated.
  - Added chapter name in header. This can be enabled by activating the `header-chapter-name` feature in the features parameter.
- **Fixes and enhancements**
  - Removed some parameters that were forced on the document like font. The template should not include something that can be specified from outside.

## 0.2.1

- Forked From [ensias-report-template](https://github.com/essmehdi/ensias-report-template)
- Updated Logos and Mentions to ones related to IMSIU
- Made the Table of Figures and Table of Tables Conditional

## 0.2.2

- Fixed the Lang issue
- Added Features from ilm
- Fixed the Tables Condition

## 0.2.3

- Codely Integration for Fancy Codeblocks

## 0.2.4

- Renamed Justfile to fulfil typst universe rules

## 0.2.5

- Fixed Table of Contents appearing without any content
- Added Dept Logo to the default template
- updated the thumbnail to match our changes

## 0.2.6

- Added CONTRIBUTING.md with guidelines following Typst Universe rules.
- Added a Contributing section to the README.
- Aligned `typst.toml` description and metadata with Universe recommendations; bumped patch version.

### 0.2.7

- Changed the Name of the Package
- Changed The Styling of Links
- Fixing the Package Check?

### 0.2.8

- Changed the Name to Remove IMSIU

### 0.2.9

- Problem with CI/CD ignore this

### 0.3.0

- Added List of Abbreviation support using the abbr package
- Added Heading level setting and default to 3 as per university guidelines
- Raised the Title and subtitle in the title page
- added Abstract and Acknowledgements as per university guidelines
- Made Table of Contents configurable by the user
- Moved the thumbnail from the template directory to the root
- Updated accent color default to the university color
