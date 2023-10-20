# apache_nifi_Template
### It is planned to create a new interface to improve the inventory system. With this interface designed according to customer needs, current data is automatically called from Microsoft Intune and transferred to the Access database at a certain time.
### Therefore, the main purpose of the project is to create an interface.
1. This interface first establishes an API connection with Intune.
2. It enables the desired data to be retrieved by filtering.
3. It first saves the data it receives into a JSON file.
4. This converts the JSON file into a CSV file.
5. It transfers this CSV file to a Datanbank such as Access.
6. The user will be able to do all these at any time he wants.
