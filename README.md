# -ubuntu-mediawiki
A mediawiki container based on ubuntu:xenial

Uses cascading builds for the time being.  Build /apache/Dockerfile first as use the image from that to build /mediawiki/Dockerfile.

Please note that you'll need to update the image name in the FROM statement from /mediawiki/Dockerfile to reflect the image name you selected when building the Apache image.

Apache image Uses PHP7.1 and Apache2.4
Mediawiki uses version/branch 1.29/REL1.29

Apache image is based on the official PHP7.1-APACHE docker.
Mediawiki image is based on the official mediawiki/mediawiki image.
