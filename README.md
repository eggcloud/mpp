# mpp (media-post-processing)
Simple utility that allows you to post-process recordings generated by Siprec 

More specifically, since Siprec recordings are basically a structured dump of RTP packets, this utility reorders them all and extracts the frames in order to stick them together and save them to a playable media file. No transcoding is done.

After that, sends a HTTP request to a server in the form of a CDR message.
