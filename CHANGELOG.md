# Changelog

All notable changes to AE Power BI Multi-Tool Suite are documented here.

---

## [v2.3.0] - Accessibility Checker Edition

### Added

- **Accessibility Checker Tool** - WCAG compliance analyzer for Power BI reports
- **Tab Order Analysis** - Keyboard navigation sequence validation
- **Alt Text Validation** - Missing and generic alt text detection
- **Color Contrast Analysis** - WCAG AA/AAA contrast checking with transparency handling
- **Page Title Checks** - Generic page title detection
- **Visual Title Checks** - Title presence and quality validation
- **Bookmark Name Analysis** - Generic bookmark name flagging
- **Hidden Page Warnings** - Accessibility considerations for hidden pages
- **Export Reports** - JSON export for compliance documentation
- **Severity Levels** - Error, Warning, Info classifications
- **Visual Classification** - Automatic detection of 30+ visual types

### Removed

- **Table Column Widths Tool** - Removed from the suite. Power BI Desktop's native table
  and matrix column auto-sizing now covers this functionality, making the dedicated tool
  redundant.

---

## [v2.2.0] - May 2026 - Connection Hot Swap Edition

### Added

- **Connection Hot Swap Tool** - Dynamic connection switching for Power BI
- **Cloud Workspace Browser** - OAuth-integrated dataset selection via MSAL
- **Preset System** - Global and model-scoped configurations with storage locations
- **Thin Report Support** - PBIP file modification (can modify while Desktop is open)
- **Pro Workspace Perspectives** - Connect to perspectives in any workspace type
- **Cloud-to-Cloud Swapping** - Switch between cloud datasets or connection types
- **Persistent Cloud Schema Cache** - Connection schemas survive app restart
- **Schema Mismatch Detection** - Warning dialog with update option
- **Smart Local Model Matching** - Automatic discovery with fuzzy matching
- **Safety Features** - Automatic backups, swap history, rollback on error

---

## [v2.1.0] - April 2026 - Field Parameters Edition

### Added

- **Field Parameters Tool** - Visual parameter creation and editing
- **Multi-level categories** - Unlimited category hierarchies with custom column names
- **Grouped view** - Collapsible category groups with drag-to-reorder
- **Virtual scrolling** - Handles 500+ fields with smooth performance
- **Category filtering** - Multi-select filter by category
- **TMDL generation** - Real-time code preview with proper formatting
- **Display name editing** - Double-click inline editing with bulk revert
- **Lineage tag preservation** - Maintains IDs when editing existing parameters
- **Category Manager panel** - Create, edit, and delete categories
- **Bulk category assignment** - Table editor for all fields

---

## [v2.0.0] - January 2026 - UI Redesign & Cleanup Edition

### Added

- **Dark/Light Mode** - Full theme support across all tools
- **Sidebar Navigation** - Redesigned for intuitive tool selection
- **Duplicate Image Detection** - MD5 hash detection with config dialog to select keeper
- **Unused Image Cleanup** - Find unreferenced images including orphan files
- **Saved Scripts Cleanup** - Remove DAX queries and TMDL scripts from semantic model
- **Multi-Diagram Optimization** - Optimize any saved diagram layout, not just default

### Changed

- **UI Consistent Theming** - Unified color system via ThemeManager
- **Layout Optimizer Scoring** - Relationship-aware 100-point scoring system with size-adjusted metrics

---

## [v1.3.1] - Cross-Page Bookmark Edition

### Added

- **Cross-Page Bookmark Mode** - Configure bookmarks to work across multiple pages without duplication
- **Cross-page UI indicator** - Link icon and page count display for cross-page bookmarks
- **Hover tooltips** - Shows which pages a cross-page bookmark spans
- **Bookmark navigator copying** - Navigators properly copied in cross-page mode

### Fixed

- Cross-page bookmarks now work on target pages (visualContainerGroups)
- Bookmarks no longer disappear after cross-page copy (comma-separated activeSection)

---

## [v1.3.0] - Cross-Page Bookmark Edition (Initial)

### Added

- Initial cross-page bookmark functionality

---

## [v1.2.0] - Sensitivity Scanner Edition

### Added

- **Sensitivity Scanner Tool** - Comprehensive TMDL scanning for sensitive data
- **Pattern-based detection** - 50+ patterns for PII, credentials, financial data, infrastructure
- **Rule Manager** - Visual pattern editor with Simple and Advanced modes
- **Custom date patterns** - User-friendly date format converter (dd/mm/yyyy to regex)
- **Pattern testing** - Real-time regex validation with test input
- **Pre-built templates** - Email, phone, credit card, IP, URLs, and 3 date formats

---

## [v1.1.1] - Advanced Copy Enhancement Edition

### Added

- **Enhanced page copying** - Multi-page support within/across PBIPs
- **Bookmark management** - Automatic bookmark and bookmark group duplication
- **Bookmark + Popup Copier** - Copy bookmarks with associated popup visuals
- **Action reassignment** - All items with actions pointing to copied pages get reassigned

---

## [v1.0.0] - Enhanced Report Cleanup Edition

### Added

- **Enhanced Table Column Widths** - Fit to Totals defaults with intelligent width calculation
- **Matrix optimization** - Hierarchy-aware spacing and improved compression

---

## [v0.0.0] - Beta Version

### Added

- **Multi-tool suite** with plugin architecture
- **Tool Manager** with automatic discovery
- **Report Merger** with conflict resolution and theme management
- **Advanced Page Copy** with dependency tracking
- **Layout Optimizer** with middle-out positioning
- **Report Cleanup** for optimization
- **Table Column Widths** tool
- Security-enhanced architecture throughout
- Professional UI with context-sensitive help

---

## Links

- **GitHub**: [AnalyticEndeavorsUser/pbi-multi-tool](https://github.com/AnalyticEndeavorsUser/pbi-multi-tool)
- **Website**: [analyticendeavors.com](https://www.analyticendeavors.com)
- **Support**: support@analyticendeavors.com
