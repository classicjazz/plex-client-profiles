In this repository are my custom XML files for Plex. These are intended for use with the latest Apple hardware, using the most recent Plex clients with the "experimental player" enabled (available only with Plex Pass).

Currently, the following profiles are included:

* an Apple TV 4K custom profile
* an iPad Pro (A10X and later) custom profile

To use a profile, you should place the XML file in the Profiles directory of your Plex Media Server's configuration files. If there is no existing Profiles folder, then you need to create it. For example, on a Synology NAS, the location of the folder should be: 

/volume1/Plex/Library/Application Support/Plex Media Server/Profiles

After you have placed the XML file in the Profiles folder, then you must restart Plex Media Server. Otherwise, the distribution default profile will be used. 

For more details, please read this article: 
https://freetime.mikeconnelly.com/archives/8172
