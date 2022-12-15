# How to create Backup?

Your Reminder app has an in-built mechanism to automatically create backup at the given frequencies. These backups will be in the form of files (text or JSON file) which will be uploaded directly to the configured backup channel.

1. In-order to start creating backups, first go to Reminder app settings (Administration -> Apps -> Reminder App -> Settings)
2.  Under the app settings, these are the 4 settings which control the backup feature. Locate these settings.\


    <figure><img src="../../../.gitbook/assets/image (22).png" alt=""><figcaption><p>Settings to configure backup</p></figcaption></figure>
3.  To enable backup, enter the "Backup Channel" setting. Here you'd need to enter the name of the channel. Note: Display name won't work, it should be the system name of the channel. You may get the name from the URL of the channel, like this

    <figure><img src="../../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Note: On newer version of the app (version 2.4.0 and above), a backup channel will automatically get created once you've installed the app. So on those versions, you may not have to do the above steps.&#x20;
{% endhint %}

Lastly, click on the **SAVE** setting button on the top right.&#x20;

If you've not created any backup before, then please **disable and re-enable the app** for the settings to take into effect. In this scenario, you should see your backup file getting generated after 6 minute.



Here's a sample backup file sent to the backup channel :tada:

<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Sample backup</p></figcaption></figure>
