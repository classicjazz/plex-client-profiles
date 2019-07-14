In this repository are my custom XML files for Plex. These are intended for use with the latest Apple hardware, the latest Plex Apple clients using the experimental player (available only with Plex Pass).

Currently, the following profiles are included:

* an Apple TV 4K custom profile
* an iPad Pro (A10X and later) custom profile

To use a profile, you should place the XML file in the Profiles directory of your Plex Media Server's configuration files. If there is no existing Profiles folder, then you need to create it. For example, on a Synology NAS, the location of the folder should be: 

/volume1/Plex/Library/Application Support/Plex Media Server/Profiles

After you have placed the XML file in the Profiles folder, then you must restart Plex Media Server. Otherwise, the distribution default profile will be used. 

For more details, please read this article: 
https://freetime.mikeconnelly.com/archives/8172

For reference, the Plex Apple tvOS/iOS client with the experimental player currently supports:

    Containers: mkv, mov, mp4, mpegts, mpeg, mpegvideo, avi, flv, ogg

    Audio codecs: aac, aac_latm, ac3, alac, flac, dca, vorbis, opus, eac3, mp1, mp2, mp3

    Video codecs: h264, hevc, vp8, vp9, h263, mpeg1video, mpeg2video, mpeg4, vc1 (in iPhone 7 and newer, iPad Pro from 2017 and newer, and in Apple TV 4K)

    Subtitle codecs: ass, dvb_subtitle, vobsub, eia_608, pgs, microdvd, movtext, ssa, srt
