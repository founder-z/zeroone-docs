# App data

In this section you can create, modify and delete app data.

{% hint style="info" %}
To make app data tab available, you need to first select data view
{% endhint %}


### Sorting
By clicking on the column headers you can sort the data.
![](<../.gitbook/assets/app-data-sorts.png>)


### Search

Using search input, you can narrow down the list of app data. It is filtering all fields in the selected view.

### Filters
By clicking on the filter button you can open the filter dialog. In this dialog you can provide complex filters.

![](<../.gitbook/assets/app-data-filters-button.png>)
![](<../.gitbook/assets/app-data-filters.png>)


### New entry

This button opens the dialog to create a new app data entry. The dialog contains all fields in the selected view.

### Import

This button opens the dialog allowing you to import app data from a csv file.
For example, to import file with this content:
```
id,slug
"abf27441-40ed-4156-ba0b-70029c74671a","test-app-data1"
"abf27441-40ed-4156-ba0b-70029c74671b","test-app-data2"
"abf27441-40ed-4156-ba0b-70029c74671c","test-app-data3"
```

you will need to select file and set `Column A` and `Column B` to `id` and `slug`.
![](<../.gitbook/assets/abf27441-40ed-4156-ba0b-70029c74671a.png>)

After clicking "OK" you will update or insert data in the selected view. If entry with this id already existed it will be updated to match the provided new data.

{% hint style="info" %}
If you provide data with existing id, the row with this id will be updated.
{% endhint %}


### Export
This button will export selected rows to a csv file.


### Delete
This button will delete selected rows.