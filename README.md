# docker-server-mac
sets up home media servers. targets arm64 mac


had to use docker VMM instead of apple virtualization framework for containers to see full disk size of external drive

note: plex linuxserver does not have support for hardware transcoding, so was excluded from the compose file
I recommend running it natively