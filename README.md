# HairSalon

### ***An [Asp.Net](http://asp.Net) MVC Web App that handles clients and their stylist within a MySQL Database***

### **By *Aaron Kauffman***

## **Description**

*This web application helps a hypothetical stylist owner manage their stylists and clientele.* 

# Instructions

1. [Import the database](https://dev.mysql.com/doc/workbench/en/wb-admin-export-import-management.html) `kauffman_aaron.sql` from the uppermost directory within the project folder into MySQL Workbench. ***Use the schema name `kauffman_aaron`.***
2. Add the file `appsettings.json` to the HairSalon folder. ***It's contents also include other MVC files and folders.***
3. Here's what `appsettings.json` should contain for this specific project. Replace your [DATABASE] and [PASSWORD] appropriately.

```json
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=kauffman_aaron;uid=root;pwd=password;"
  }
}
```

1. From the uppermost directory of your project run:

```bash
cd HairSalon && dotnet run
```

## **Technologies Used**

- C#, MVC, [Asp.Net](http://asp.Net) Core, EF Core, MySQL
- HTML, JS, CSS, Bootstrap, git

## **Known Bugs**

- *If user ignores warnings about adding client before stylist MySQL will throw errors.*

## **License**

[MIT](https://choosealicense.com/licenses/mit/)

## **Contact Information**

*If you run into any issues, remember: Stop, Drop, and Roll. Or, Contact Aaron at: [Aaron.Christian.Kauffman@gmail.com](mailto:Aaron.Christian.Kauffman@gmail.com)*
