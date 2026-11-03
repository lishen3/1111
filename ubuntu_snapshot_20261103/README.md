# Ubuntu source snapshot

Source: /home/piaosen/sentry_nav_ws/src/icd27_sentry-20261029
Original Ubuntu source unchanged. Build/install/log/backups excluded.
27 LFS pointer placeholders excluded at user request; see excluded_lfs_pointers.json. Their model resources are not included.

Reassemble and extract on Ubuntu:

    cat source.tar.gz.part* > source.tar.gz
    sha256sum -c SHA256.txt
    mkdir -p src/icd27_sentry-20261029
    tar -xzf source.tar.gz -C src/icd27_sentry-20261029
