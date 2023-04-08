# webprintingapp-alpha
Alpha testing of new releases of GRIPS Web Printing Application.
This repo is only to be used for Alpha-testing.

To use this repo, change your setting in GRIPS Web Printing Application.exe.config:
  <applicationSettings>
    <NAVPrintingApplication.Properties.Settings>
      <setting name="GitHubPath" serializeAs="String">
        <value>https://github.com/grips-tiresoft/webprintingapp-alpha</value>
      </setting>
    </NAVPrintingApplication.Properties.Settings>
  </applicationSettings>

Note: after an update this will revert back to the default of:
https://github.com/grips-tiresoft/webprintingapp
