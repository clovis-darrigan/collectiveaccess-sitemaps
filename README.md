# collectiveaccess-sitemaps
PHP script generating a sitemaps.xml file in Pawtucket's root.
Extract informations directly from SQL database for Collections, Objects, Places, Occurrences, Entities.

1. Edit the file to replace "your_database" by the real name of your database, "your_password" by the real password, and 127.0.0.1 by your server. Edit $absolute_path and $URL_root.

2. Choose your settings for generating the sitemaps.xml file. Read comments in the file.

3. Execute: php -f sitemaps.php

   The script gives you informations, such as numbers of URLs created for each kind of items (Collections, Objects, Places, Occurrences, Entities and Total)

   If the "lastmod" date is "1970-01-01CET01:00:00+01:00" for an item, it displays a warning with ID of the item.

4. Check if sitemaps.xml file is well created in your Pawtucket's public root, and readable by bots.
