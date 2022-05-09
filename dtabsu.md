# Database

The database manages the data that users create when using the app. Here you can configure and view the data in your app's database.

### Create a new table

You can create a new table by clicking on `Create a new table` button, and entering the name of the table.

![](<.gitbook/assets/image (4) (1) (1) (1) (1).png>)

### Edit

You can change the table name from the pen icon.\
<img src=".gitbook/assets/image (8) (1) (1) (1).png" alt="" data-size="original">

{% hint style="info" %}
User table cannot be editted.
{% endhint %}

### Delete

You can delete the table from the trash can icon.

![](<.gitbook/assets/image (5) (1) (2).png>)

{% hint style="info" %}
User table cannot be deleted
{% endhint %}

## Custom type

There are default fields when you create the table.

### Id

The unique ID of the record. The type is [UUID](https://www.postgresql.org/docs/current/datatype-uuid.html).

### Created\_at

Stores the date and time when the record was created. The type is `date`

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

##

###
