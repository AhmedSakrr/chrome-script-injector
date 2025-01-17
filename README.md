![Icon](src/icon48.png) Fanplayr Script Injector
============================================

A Chrome browser extension for injecting scripts based on the browser url.

## Installation

1. Download the extension here, <https://github.com/fanplayr/chrome-script-injector/archive/master.zip>.
2. Extract the zip file.
3. Navigate to <a href="chrome://extensions" target="_blank">chrome://extensions</a> in Chrome.
4. Ensure the **Developer mode** option is checked.
5. Click the **Load unpacked extension** button.
6. Browse to the folder that was created when you extracted the zip file and click **Select**.

The extension should now be installed.

## Usage

### Creating a new rule

1. On **any** webpage, right-click and select **Fanplayr > Script Injector**.
2. Click the **New Rule** button at the bottom to define a new rule.
3. Enter the website's domain, url or pattern to match against.
    - Enter the customer's domain, for example `*fanplayr.com*` to have this rule run on any page on http://www.fanplayr.com. 
4. Enter the script's url or content.
5. Click **Save Changes**.
6. Enable the rule you just added.

The script should be automatically injected into the url you defined the next time you visit it.


### Backing up settings

1. Open the extension options by right-clicking any page and selecting **Fanplayr > Script Injector**.
2. Click **Backup / Restore Settings**.
3. Copy the JSON text and store it in a safe location.

### Restoring settings

1. Open the extension options by right-clicking any page and selecting **Fanplayr > Script Injector**.
2. Click **Backup / Restore Settings**.
3. Paste the JSON text you previously saved into the text area.
4. Click **Restore**.


https://www.youtube.com/watch?v=_-FCWwC9XQA&feature=youtu.be
