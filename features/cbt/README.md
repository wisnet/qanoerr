## Files
*  `behat-cbt.hbs.yml`: is the `behat` template.  When processed, the `{{variables}}` are replaced w/ the values from the `devices.json`
*  `browser-devices.json`: was produced using the `getBrowsers.sh` script.
*  `devices.json`: contains those devices/browsers that will tested on CrossBrowserTesting.
*  `cbt.env.json.example`: copy this to `cbt.env.json` and update the values from you `CrossBrowserTesting.com` userid/authkey
*  `device.hbs.html`: is the template for reporting the results of the Gherkin
*  `getBrowsers.sh`: Script the returns all the devices/browser supported by CrossBrowserTesting
*  `.gitignore`: When the `behat-cbt.hbs.yml` is processed, the file `behat-cbt.yml` is generated and used to run the specific browser/device.  This file does not need to be committed to Git.  Also, the `cbt.env.json` file will contain your `CrossBrowserTesting` credentials so that too, should not be committed to Git.
