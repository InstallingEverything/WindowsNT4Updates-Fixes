# Updates

A structured list of Windows NT 4.0 system fixes, Internet Explorer patches, and Media Player updates included in this collection.

## Overview

This section organizes available updates into system updates, IE security updates for IE6 SP1, and Windows Media Player 6.4 updates.

## Windows NT 4.0 System Updates

- Q238934i - A program using a secure (SSL) connection may stop responding when leaving the connection to the secure server.
- Q245148i - A change to Winlogon.exe in Service Pack 6 may cause it to hang when you Close all programs and log on as a different user.
- Q258437i - GetEffectiveRightsFromAcl fails in Service Pack 6. A buffer overload can cause a server to take control. Only concerns the NT4 SP6a version.
- Q278499i - Indexing Services cross-site scripting vulnerability.
- Q304158i - HyperTerminal contains an unmonitored buffer allowing code execution.
- Q305399i - Resolves the "Malformed RPC Packet" security vulnerability in Windows NT 4.0.
- Q305929i - After installing the SRP, connecting to an SSL-secured site may display an error message even if the certificate is valid.
- Q312895i - Unmonitored buffer can allow code execution.
- Q314147i - Unmonitored buffer in SNMP services can allow malicious code execution and denial of service. (Only affects NT4 SP6a.)
- Q318138i - Unmonitored buffer problem in the RRAS function.
- Q318203i - Patch available for XMLHTTP vulnerability.
- Q321599i - IIS4 heap overrun in HTR chunked encoding could enable web server compromise.
- Q320206i - In debugging mode, a program can take more privileges than it has.
- Q323172i - Security flaw allows a website or email to erase digital certificates and use their services.
- Q326830i - Fault causing denial of service and crash of an SMB server.
- Q327696i - IIS4 Internet Information Services Security Roll-up Package.
- Q328310i - Security patch: flaw in Windows WM_TIMER.
- Q329115i - Certificate validation vulnerability could allow remote control of a machine.
- Q810833i - Location service maps logical names to network names. An unmonitored buffer can allow code execution.
- Q811493i - Buffer overrun in Windows kernel message handling could lead to elevated privileges.
- Q815021i - Unmonitored buffer in the WebDAV protocol can allow code execution on an IIS server.
- Q817606i - SMB protocol flaw can allow malicious code execution.
- Q819696i - Two unmonitored buffers can allow an attack via a MIDI file hosted on a website.
- Q823492i - Error message when using named pipes.
- Q823803i - Flaw in a Windows function may allow denial of service.
- KB840315 - Security update for HTML Help vulnerability (840315).
- KB890175 - Vulnerability in HTML Help could allow code execution.
- KB917344 - Kernel vulnerability with cursors, animated cursors, and icons may cause DoS.
- KB870669 - Critical update for ADODB.Stream.

## Internet Explorer Updates

**For IE6 SP1**

- KB833989 - Security issue that could allow an attacker to compromise a computer and gain control.
- KB841873 - Vulnerability in Task Scheduler could allow code execution.
- KB887797 - Cumulative update for Outlook Express.
- KB889293 - Security update to fix a buffer overflow vulnerability in Internet Explorer.
- KB889669 - Cumulative security update for Internet Explorer 6 Service Pack 1.

## Windows Media Player 6.4 Updates

- WM320920_64.exe - Security update for Windows Media Player 6.4.
- WM308567 - ASF processor contains unchecked buffer.
- WMPCDCS8.exe - Windows Media 8 Codec Package.

## Notes

- Apply system updates before browser and media updates when possible.
- The IE updates are specific to IE6 SP1.
- Always test in a VM snapshot before installing updates in a live environment.

