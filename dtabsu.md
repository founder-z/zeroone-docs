# Database

The database manages the data that users create when using the app. Here you can configure and view the data in your app's database.

### Privacy rules

You can transition to the Privacy rules tab. Here you can configure conditions for each table's permissions to read, edit, delete or create data.&#x20;

### Create a new table

You can create a new table by clicking on `Create a new table` button, and entering the name of the table.

![](<.gitbook/assets/image (4).png>)

### Edit

You can change the table name from the pen icon.

### Delete

You can delete the table from the trash can icon.

## Table

The data in the app's database will be listed. Display data by data type. You can create, edit, and delete specific fields in the database.

## Custom type

These fields are automatically defined when you create the table. These also apply to the user's table.

### Id

The unique ID of the field. The data type is to search for.

### Created\_at

Stores the date the field was created. The data type is date.

### Updated\_at

Stores the date the field was last edited. The data type is date.

## Custom field

Define a new field in the table.

### Field

The field requires a data type. Numbers, texts, yes / no, dates, files, etc. You can also choose the name of a table that already exists to create the relation.

### Add field

You can set the field name, data type, unique value, default value and create a new field.

### Unique value

Select a unique value to display the unique ID of the field.

## User

In the user table, in addition to the custom fields, the following specific fields are displayed by default.

### Email email

Stores the registered user's email. The data type is string.

### Phone

Stores the phone number of the registered user. The data type is string.

### Role

A group or template of users. It is created according to the type of user (administrator, developer, general user, etc.), and a role value is assigned to each user. The data type is string.

### Is\_super\_admin

Stores either "yes / no" as to whether the user is an app administrator. The data type is boolean.

### Email\_confirmed

Stores the confirmation email usage used for user registration as either "Yes / No". The data type is boolean.

### Phone\_confirmed

Stores the use of the confirmation phone number used for user registration as either "Yes / No". The data type is boolean.

## App data

The data in the app's database is displayed. Display data by data type and display specific fields in columns. You can also create, modify, delete specific fields in the database, or upload them in bulk,

### Search

You can search the field.

### Filter

You can narrow down the data you want to display in the list.

### New input

You can create a new field.

### Import

Import the database information.

### Bulk

Collectively manage data.

## Privacy rules

Privacy allows users to set rules regarding the display of different types of data.

###
