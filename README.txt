===================INSTALATION=================

1. BACKUP EVERYTHING.
2. Copy avactis-system and avactis-themes folder to yout Avactis directory.
3. Go to avactis-conf/cache and delete all files. 
4. add following line to /avactis-system/shortname2path file

PM_WTP = "avactis-system/admin/templates/resources/payment-module-wtp-messages-eng.ini"

5. Import data.sql file to your database.

Refresh payment module list in Admin area, Paysera.com payment module should appear as active and selected.

If any problems occur please report to support@paysera.com