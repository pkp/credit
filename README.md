# CRediT plugin for OJS

This plugin adds support for the NISO CRediT contributor role standard in OJS.
It is a work in progress, started at the 2022 Helsinki sprint.

**This plugin is not complete. Do not attempt to use it if you're not sure!**

Working group:

- Esko Clarke Sario: Finnish Lifelong Learning Foundation (Kvs)
- Alec Smecher: Public Knowledge Project
- Frederique Belliard: Delft University of Technology - Library

## Configuration

The plugin provides the following settings:

1. **Show CRediT roles by author names on article landing pages** - When enabled, CRediT roles will be displayed next to author names on article pages.

2. **Require at least one CRediT role for each contributor** - When enabled, editors must select at least one CRediT role for each contributor. The contributor form will validate this requirement.

## Usage

After enabling the plugin:

1. Go to Settings > Website > Plugins > Generic Plugins
2. Find "CRediT Plugin" and click "Settings"
3. Enable/disable the options as needed:
   - Check "Show CRediT roles..." to display roles on article pages
   - Check "Require at least one CRediT role..." to make role selection mandatory
4. Save your settings

When editing contributors in submissions, you will see the CRediT roles available for selection. If the "require" option is enabled, you must select at least one role before saving.