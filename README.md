# omeka_upgrade
Our steps to automate and upgrade Omeka sites.

1. Retrieve fresh backup from the database of the original Omeka site.
2. Forked the Omeka repository and cloned that into the new Omeka server.
3. Copy the up-to-date Omeka install into the old Omeka-site folder, to overwrite the existing files with updated ones.
4. Verify/configure .ini files (db.ini, config.ini, debug.ini) and .htaccess file.
5. Ensure server allows mod rewrite and listens to .htaccess.
6. Create super user account to the database.
7. Access site on the web and complete the "upgrade database" set if necessary.
8. Login to the admin panel with the super user.
9. If plugins outdated, deactivate old plugin, and download new version.
10. Address any navigation issues.
    
