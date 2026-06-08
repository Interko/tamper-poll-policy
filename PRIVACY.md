# Privacy Policy

## Interko Poll Tamper

Interko Poll Tamper is a lightweight browser extension designed to improve the responsiveness of Niagara Hx / PX browser pages by allowing the user to configure the browser polling interval.

## Data Collection

Interko Poll Tamper does **not** collect, transmit, sell, share, or store any personal data on external servers.

The extension does not use analytics, tracking scripts, advertising services, remote logging, or third-party data collection services.

## Data Stored Locally

The extension stores only the settings required for its functionality:

* Whether the extension is enabled or disabled
* The configured polling delay in milliseconds
* The optional IP address / host filter entered by the user

These settings are stored using the browser extension storage API. The data remains within the user’s browser environment and is used only to restore the user’s selected configuration.

## Website Access

The extension can run on web pages matching Niagara Hx / PX style URLs, such as pages using `/ord`, `/hx`, or `/px`.

The extension only modifies browser-side polling behavior when the Niagara `hx` object is present on the page and when the extension is enabled by the user.

If the optional IP address / host filter is configured, the extension only runs its polling modification logic on the specified IP addresses or hostnames.

## Network Activity

Interko Poll Tamper does not create external network requests of its own.

When enabled, it may cause the existing Niagara Hx / PX page to poll the Niagara station more frequently, based on the polling delay configured by the user. This affects only communication between the user’s browser and the Niagara system already opened by the user.

## No Remote Code

The extension does not download or execute remote code. All extension code is included locally within the extension package.

## No Credentials Access

The extension does not read, store, collect, or transmit usernames, passwords, authentication tokens, cookies, or Niagara credentials.

## User Control

The user can enable or disable the extension at any time using the extension popup.

When disabled, the extension restores the Niagara Hx polling timeout to the default value used by the extension, which is 5000 milliseconds.

## Intended Use

This extension is intended for testing and internal operational use with Niagara Hx / PX browser interfaces. Very low polling intervals may increase browser, network, and Niagara station load. Users should choose polling values appropriate for their environment.

## Changes to This Policy

This privacy policy may be updated if the extension’s functionality changes.

## Contact

For questions about this extension or this privacy policy, contact Interko.
