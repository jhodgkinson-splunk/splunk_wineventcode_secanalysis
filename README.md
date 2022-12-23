# splunk_wineventcode_secanalysis

REQUIRES COMMON INFORMATION MODEL 4.14+ with properly populated signature_id field!

12-23-22: I have returned to Splunk and will be updating this app soon to include some new sources!
Then, perhaps finally get this on Splunkbase.

Version 1.4 of Windows Event Code Security Analysis app for Splunk. Direct questions to @james_brodsky on Twitter.
As of January 2022 I have left Splunk and am employed at Okta, but happy to maintain this app as time permits.

Thanks to all security researchers that provided public info on event code recommendations - sources for this
are linked from the Lookup Overview page, Count of Codes by Authority panel.

If you want a .spl version of this look in the root of this repo - removed temporarily but will put it back soon!

01-30-22: Merged in addition of JSCU-NL Logging Essentials guidance, thank you David Andre!

05-17-21: Added Defender event codes to lookup; fixed readme format. Thank you Drew Church!

01-27-21: Fixed lookup link to ACSC guidance.

01-12-21: Fixed a bug with missing host input, fixed drilldowns from timecharts.

01-07-21: updated lookup for code 1007,1200,1202,307,510.

12-25-20: added Golden SAML event code guidance.

10-09-20: added an option to specify index wildcards.

10-08-20: added Splunk UBA event codes from [Splunk docs](https://docs.splunk.com/Documentation/UBA/latest/GetDataIn/WindowsEvents) - thank you @drewchurch.

09-14-20: added auto lookup support for XML data sources, added a few new event volume changes to main lookup.

06-11-20: added support in four dashboards for the Event Signatures data model. You must have CIM 4.14+ and you must have accelerated your data in the Event Signatures data model for improved dashboards to work. Windows TA 8.0+ supports population of the critical signature_id field needed.

04-18-20: added Australian Signals Directorate/ACSC's latest event code guidance.
