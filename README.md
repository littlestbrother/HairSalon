# HairSalon

1. [Import the database](https://dev.mysql.com/doc/workbench/en/wb-admin-export-import-management.html) `kauffman_aaron.sql` from the uppermost directory within the project folder into MySQL Workbench. ***Use the schema name `kauffman_aaron`.***
2. Add the file `appsettings.json` to the HairSalon folder. ***It's contents also include other MVC files and folders.***
3. Here's what `appsettings.json` should contain for this specific project. Replace your [DATABASE] and [PASSWORD] appropriately.

```json
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[DATABASE];uid=root;pwd=[PASSWORD];"
  }
}
```
4. From the uppermost directory of your project run:

```bash
cd HairSalon && dotnet run
```
