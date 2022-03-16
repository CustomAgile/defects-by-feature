Defects by Feature
=========================

## Overview
Given a Feature, find the defects that are associated with a story that's associated with the feature.

## Development
This was written using p5, but needs a later version than p5 is pinned to.  So after compiling, you MUST
append "?wsapiVersion=1.43" to the sdk link in the App.html file or the App-debug.html file, like this:

    <script type="text/javascript" src="/apps/2.0p5/sdk.js?wsapiVersion=1.43"></script>

in the debug app:

    <script type="text/javascript" src="https://testme.rallydev.com/apps/2.0p5/sdk-debug.js?wsapiVersion=1.43"></script>

This is only necessary when you rebuild, because the rebuilder will overrite the setting.


## License

AppTemplate is released under the MIT license.  See the file [LICENSE](./LICENSE) for the full text.

##Documentation for SDK

You can find the documentation on our help [site.](https://help.rallydev.com/apps/rc2/doc/)
