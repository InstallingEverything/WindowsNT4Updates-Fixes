# Apps

A curated list of Windows NT 4.0 application packages included for installation.

## Overview

This section contains core runtime components, media support, database libraries, and multiple versions of Internet Explorer for compatibility testing.

## Included Packages

### Microsoft Apps

- Microsoft Windows Installer (`1.1`)
- Microsoft .NET Framework 1.1 (`1.1.4322`)
- Microsoft Windows Media Player 6.4 (`6.4.05.0809`)
- Microsoft JET 4.0 SP8 (`KB829558`)

### Microsoft Internet Explorer

- Internet Explorer 3.0 (`4.70.1155`)
- Internet Explorer 3.02 (`4.70.1300`)
- Internet Explorer 4.0 (`4.71.1712.6`)
- Internet Explorer 4.01 SP1 (`4.72.3110.3`)
- Internet Explorer 4.01 SP2 (`4.72.3612.1707`)
- Internet Explorer 5.01 (`5.00.3314.2101`)
- Internet Explorer 5.5 (`5.50.4807.2300`)
- Internet Explorer 5.51 (`5.51.4807.2300`)
- Internet Explorer 6 SP1 (`6.0.2800.1106`)

## Notes

- Install dependencies in order: Windows Installer, then .NET if required by additional applications.
- Use the IE version that best matches your application compatibility needs.
- Test installs in a VM snapshot before applying to a production image.