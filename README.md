# ubuntu-mediawiki
A mediawiki container based on reference images PHP7.1-APACHE and mediawiki/mediawiki.  Please consult their pages for more detailed operation instructions until I have time to write a more flushed out description.

This build includes Mediawiki (branch REL1.29), Node (v6), and Parsoid (developer installation) as well as VisualEditor.  

Parsoid's config is located in /usr/lib/parsoid/config.yaml

VisualEditor and Parsoid must be enabled and further configured to communicate via LocalSettings.php which is not included in this build

The root directory for Mediawiki is /var/www/html and this is also where LocalSettings.php must be generated or placed in.

This is very much a work in progress, feel free to fork and pull and suggest improvements as needed.
