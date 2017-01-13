# FreeNAS-Gogs
Gogs (gogs.io) install an update script for FreeNAS (and any FreeBSD Jail)

    cd /tmp
    fetch --no-verify-peer https://github.com/jedediahfrey/FreeNAS-Gogs/archive/master.zip
    unzip master.zip
    cd FreeNAS-Gogs-master
    chmod +x gogs-root.sh
    ./gogs-root.sh

During initial setup, select "SQLite3" database type.

Final gogs folder is /usr/home/git/gogs/
