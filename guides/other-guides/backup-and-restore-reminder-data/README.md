# Backup and Restore Reminder Data

{% hint style="info" %}
This guide is built for Workspace **Admins**
{% endhint %}

{% hint style="info" %}
Available on App version 2.4.0 and above
{% endhint %}

We highly recommend creating frequent backups of your Reminder data. This will help you recover from unforeseen outages where your Reminder app becomes unusable and you have to **uninstall the app & reinstall it**. \
\
Note: Based on the architecture of Rocket.Chat apps, once an app is uninstalled, then all its corresponding data automatically gets deleted - which means if you have users who have reminders created before an outage, those will be lost when you have to reinstall the app. In such a scenario, it is quite useful having a backup of your Reminder data so you can quickly recover from the outage and don't affect your workspace user's operation.

{% content-ref url="how-to-create-backup.md" %}
[how-to-create-backup.md](how-to-create-backup.md)
{% endcontent-ref %}

{% content-ref url="how-to-restore-your-backup.md" %}
[how-to-restore-your-backup.md](how-to-restore-your-backup.md)
{% endcontent-ref %}
