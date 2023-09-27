<p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Firefox_logo%2C_2017.svg/2048px-Firefox_logo%2C_2017.svg.png" width="230"></a>
<h1 align="center"><b>Disable Firefox Telemetry & Data Collection</b></h1>

<br />
<br />

## About
Mozilla has provided numerous settings that can be modified on the `Options Page` which determines how your copy of Firefox communicates with Mozilla. <br /><br />
You can enable/disable settings such as
- `Allow Firefox to send technical and interaction data to Mozilla`
- `Allow Firefox to install and run studies`
- `Allow Firefox to send Crash Reports to Mozilla Servers`

<br />

These settings are available within the **Privacy & Security** section of your browser. 

<br />

## Disable Telemetry and Data Collection:
- Launch Firefox, type `about:config` in the address bar.
  - If you get a warning prompt, select `Accept the Risk and Continue`.
- In the search bar, type each of the below settings and set them to the value provided in the right column:
  
<br />

Setting | Change To |
| --- | --- |
| browser.newtabpage.activity-stream.feeds.telemetry | false |
| browser.newtabpage.activity-stream.telemetry | false |
| browser.ping-centre.telemetry | false |
| datareporting.healthreport.service.enabled | false |
| datareporting.healthreport.uploadEnabled | false |
| datareporting.policy.dataSubmissionEnabled | false |
| datareporting.sessions.current.clean | true
| devtools.onboarding.telemetry.logged | false |
| toolkit.telemetry.archive.enabled | false |
| toolkit.telemetry.bhrPing.enabled | false |
| toolkit.telemetry.enabled | false |
| toolkit.telemetry.firstShutdownPing.enabled | false |
| toolkit.telemetry.hybridContent.enabled | false |
| toolkit.telemetry.newProfilePing.enabled | false |
| toolkit.telemetry.prompted | Number Value 2 |
| toolkit.telemetry.rejected | true
| toolkit.telemetry.reportingpolicy.firstRun | false |
| toolkit.telemetry.server | Delete URL |
| toolkit.telemetry.shutdownPingSender.enabled | false |
| toolkit.telemetry.unified | false |
| toolkit.telemetry.unifiedIsOptIn | false |
| toolkit.telemetry.updatePing.enabled | false |
