Matillion ETL Backup
=================

Jobs, environments and variables can be exported from one Matillion ETL instance as an alternative backup method. This can be accessed through Project → Export. These menus allow the user to select multiple pieces of their Matillion setup to export to a JSON file that can be later imported to the instance.


Note:
=========

If an imported job has the same name as an existing job, it will be given a numbered suffix when imported.
Exported jobs are not removed or altered in any way from the original instance.
It is not recommended that users manually edit the JSON file.
You cannot import resources from a newer version Matillion ETL instance into an older version Matillion ETL instance.