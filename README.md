# Function---Get-Customer-ID
Provided a customer name, this will return the Syncro customer ID as well as the item ID from our SharePoint master client list.  

It can match on several fields, helpful for when the customer name may be different ('and' instead of &) or shortened.  In our environement, we have the proper, offical customer name, a 3-char shortname, and then two alternate name fields.

The flow will return the Syncro customer ID, the SharePoint list item ID, and the proper full customer name.
If no match is found, you can define a fallback customer name and ID.


![screencapture-us-flow-microsoft-manage-environments-Default-57be6827-a78e-4992-a0f2-edd3e4226e8f-flows-f651e67a-7459-4897-9aca-0ca7805fbf6f-2021-06-21-14_51_04](https://user-images.githubusercontent.com/49880736/122813506-088da400-d2a1-11eb-93b3-f1f74dae9417.png)
