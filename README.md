# collectiveaccess-sitemaps
PHP script generating a sitemap.xml file in Pawtucket's root.
Extract informations directly from SQL database for Collections, Objects, Places, Occurrences, Entities.

1. Edit the file to define parameters for SQL connection. You can copy/paste these lines from setup.php file.
   Edit $absolute_path and $URL_root.

2. Choose your settings for generating the sitemap.xml file. Read comments in the file.

3. Execute: php -f sitemap.php

   The script gives you informations, such as numbers of URLs created for each kind of items (Collections, Objects, Places, Occurrences, Entities and Total)

   If the "lastmod" date is "1970-01-01CET01:00:00+01:00" for an item, it displays a warning with ID of the item.

4. Check if sitemap.xml file is well created in your Pawtucket's public root, and readable by bots.
