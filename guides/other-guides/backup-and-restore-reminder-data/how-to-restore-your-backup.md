# How to restore your Backup?

#### Pre-requisite:&#x20;

* A backup file created and sent to the backup channel. [Click here](how-to-create-backup.md) to know more
* An API platform (like Postman) to send an HTTP request



#### Here's the guide to restore a backup file

1.  First, grab the link to the respective backup file you wish to restore. You can get the file from the backup channel (Hover over the txt or json file -> Click on 3 dots -> Click "Get Link"). A backup link should be in the following format `http://localhost:3000/group/reminder-app-backup?msg=DYg8efuxbgmPYxFQH`

    <figure><img src="../../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>
2.  Next, we need to get the API URL for the endpoint which we'll be using to restore the backup. You can get it by going to Reminder app's details panel. On the details panel, locate the API section and grab the URL ending with `restoreBackup`

    <figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Restore backup API URL</p></figcaption></figure>
3. Next use your favorite API platform (like Postman) to send an API request to the URL you got in step 2. The request should be JSON based and should have a property named `backupFileUrl` , which is the message URL you got in step 1. Here's a sample request

```markup
curl --location --request POST 'http://localhost:3000/api/apps/private/7a8cd36b-5f7b-4177-bd7f-bfc9be908bf8/B4sjGGNj4gGY2yhh6/restoreBackup' \
--header 'Content-Type: application/json' \
--data-raw '{
    "backupFileUrl": "http://localhost:3000/group/reminder-app-backup?msg=DYg8efuxbgmPYxFQH"
}'
```

<figure><img src="../../../.gitbook/assets/image (23).png" alt=""><figcaption><p>Sample request</p></figcaption></figure>



Once you initiate the restoration process, you can check the backup channel to get updates about the restoration step

<figure><img src="../../../.gitbook/assets/image (32).png" alt=""><figcaption><p>Restoration process confirmation</p></figcaption></figure>

And that was about it. By now, you should have your Reminder data restored :tada:
