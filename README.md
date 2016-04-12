***
# SublimeDataSiftPYLON - DataSift PYLON CSDL Validate/Compile plugin for Sublime Text 3
***
====================

Contact: [sam.aybar@datasift.com](mailto:sam.aybar@datasift.com)

##Summary
Makes HTTP requests to the Validate and Compile PYLON Endpoints. Will tell if you have valid CSDL or return the hash for the CSDL.

## Installation
###Recommended
Using the Sublime Text 3 Package Control plugin (http://wbond.net/sublime_packages/package_control)
press *CMD + SHIFT + P* (on OS X) and find **Package Control: Add Repository** and press *Enter*. Paste in the url for this Github repository (https://github.com/samaybar/SublimeDataSiftPYLON) Then *CMD + SHIFT + P* then Install Package and find this plugin in the list by name **Sublime DataSift PYLON**.

###Alternate
Or git clone to your Sublime Text 3 packages folder directly (usually located at /Sublime Text 3/Packages/User/).

## Configuration
Add your PYLON authorization/api key to your Sublime Preferences.sublime-settings file (press *CMD + ,* on OS X)
```json
{
    "pylon_auth": "USERNAME:APIKEY"
}
```
## Usage
From context Menu, select **Validate CSDL** to validate, **Compile CSDL** to compile. If these commands are grayed out, copy the pylon_compiler.py file from the sublimedatasiftpylon directory to the parent directory.
Or, select from Command Pallete (*CMD + SHIFT + P*)
Keyboard shortcuts:
Validate - *CTRL + ALT + V*
Compile - *CTRL + ALT + C*