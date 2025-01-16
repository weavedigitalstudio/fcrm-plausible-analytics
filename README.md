# FireHawk CRM Tributes - Plausible Analytics Integration

A simple integration for the FireHawkCRM tributes plugin which adds the Plausible Analytics tracking code to the dynamically created individual funeral/tribute pages.

This will add your tracking code to your individual tributes/funerals so you can see visitor and pageviews for each in Plausible.

Plausible Analytics is a privacy-focused, easy-to-use, open source, lightweight (<1 KB) and privacy-friendly web analytics alternative to Google Analytics.

Plausible Analytics doesn’t use cookies and is fully compliant with GDPR, CCPA and PECR. Made and hosted in the EU, powered by European-owned cloud infrastructure 🇪🇺.

FireHawk CRM and their WordPress tributes plugin are from [FireHawk Funerals](https://firehawkfunerals.com)

---

## Our extensions for funeral websites and the FireHawk CRM Tributes Plugin.
This is part of a small family of complimentary plugins we've developed to extend FireHawkCRM Tributes functionality for our use building funeral websites in WordPress.

For a complete tribute management solution and CRM, consider trying FireHawkCRM and our other add-ons:

- [FCRM Enhancement Suite](https://github.com/weavedigitalstudio/fcrm-enhancement-suite):
A collection of enhancements and additional features for the FireHawkCRM Tributes plugin that improve the site performance, user experience, and functionality of tribute pages in WordPress.

- [FCRM SEOPress Integration](https://github.com/weavedigitalstudio/fcrm-seopress):
If you use SEOPress on your WordPress site, this replaces the current bundled YoastSEO integration of the FireHawkCRM Tributes plugin with added support for SEOPress and SEOPress Pro. Meta titles and tags are then controlled by SEOPress.

- [FCRM Plausible Analytics](https://github.com/weavedigitalstudio/fcrm-plausible-analytics):
Integration for FireHawkCRM Tributes plugin which adds Plausible Analytics tracking code to the individual funerals/tribute pages. Plausible is a privacy-focused analytics to track tribute engagement while respecting visitor privacy. We recommend Plausible instead of Google Analytics.

---

## Installation from GitHub
When installing this plugin from GitHub:
1. Go to the [Releases](https://github.com/weavedigitalstudio/fcrm-plausible-analytics/releases) page
2. Download the latest release ZIP file
3. Extract the ZIP file on your computer
4. Rename the extracted folder to remove the version number  
   (e.g., from `fcrm-plausible-analytics-1.1.0` to `fcrm-plausible-analytics`)
5. Create a new ZIP file from the renamed folder
6. In your WordPress admin panel, go to Plugins → Add New → Upload Plugin
7. Upload your new ZIP file and activate the plugin
8. Plugin should then auto-update moving forward if there are any changes.

**Note**: The folder renaming step is necessary for WordPress to properly handle plugin updates and functionality.

---

## Requirements

This plugin requires:
- [FireHawkCRM Tributes](https://firehawkfunerals.com) plugin
- A [Plausible](https://plausible.io) account or the self-hosted version.
- [Plausible Analytics WordPress plugin](https://wordpress.org/plugins/plausible-analytics/) installed, activated and linked to your site.
- WordPress 6.0 or higher
- PHP 7.2 or higher

The plugin will automatically check for the required plugins and show an admin notice if they're not active.

---

## ⚠️ Important Notice

This plugin is primarily developed for internal use at Weave Digital Studio & Human Kind and with our funeral websites we build. While we're making it available publicly, please note:

- Features and updates are driven by our specific needs and client requirements
- Testing is conducted only within our controlled environments
- We cannot guarantee compatibility with all WordPress setups or themes
- No official support is provided for external users
- Use in production environments outside our ecosystem is at your own risk

We encourage you to test thoroughly in a staging environment before any production use.

---

## Credits

- Developed by [Weave Digital Studio](https://weave.co.nz) in New Zealand.
- FireHawkCRM and their WordPress tributes plugin are from [FireHawk Funerals](https://firehawkfunerals.com).

![Plugin Icon](icon-256x256.png)


## Changelog

## Version 1.1.0
- Added checking for required plugins
- Updated README

## Version 1.0.0
- Initial Release