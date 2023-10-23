# Daylight Saving's guide

Currently, the app isn't smart enough to detect and apply Daylight savings on its own. While we're thinking of ways to solve and address this problem due to the nature of Rocket.Chat apps and it's architecture, we've not been able to find a permanent solution to this.



For this reason, we're temporarily introducing 2 new slash commands for admins of a workspace to manually apply Daylight Saving time changes on all the reminders on their workspace all at once.&#x20;

Here are the commands:

```
/remind dst forward

OR

/remind dst backward
```

The former command will shift all ACTIVE reminders forward by an hour and vice versa.

{% hint style="warning" %}
Warning: We highly recommend creating a backup of all your reminder data before running this command.

[backup-and-restore-reminder-data](backup-and-restore-reminder-data/ "mention")
{% endhint %}



PS: I know this isn't an ideal solution. The ideal would be if the app was smart enough to automatically apply these changes on its own. However, we're unfortunately not there yet but I'll keep exploring ideas to make this happen. In the meantime, I hope this command gives you an option to at least bulk update all reminders which is kind of better than the previous version where you'd have to manually go and update them individually.
