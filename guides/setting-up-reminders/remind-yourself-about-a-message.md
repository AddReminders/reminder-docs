# Remind yourself about a message

{% hint style="info" %}
Available on Version 2.0.0 and above
{% endhint %}

1. Hover over a message.
2. Click the **three dots icon** in the top-right corner of the message.
3. Click on **Remind me about this**.
4. Choose when you'd like to get reminded about this message from the given timeframes, or select **Custom** to set your own.
5. (Optional) Add a note regarding this reminder.

{% embed url="https://www.loom.com/share/7dfe89ba196849b0b7a1bca8c755d25c" %}
Remind yourself about a message in Rocket.Chat
{% endembed %}

### Reminder Notification

When the reminder is due, then you'll receive a notification from the Reminder bot. The reminder notification will contain a link to the message which you asked to be reminded about, along with a small preview of the message.

![Reminder notification with linked message](<../../.gitbook/assets/image (18).png>)

{% hint style="info" %}
Note: If you don't the message preview, it might be because the "remind.bot" doesn't have access to the message. This might be the case when your message is from a private channel. You can solve this by inviting the bot to channel to the corresponding channel using the "/invite remind.bot" command
{% endhint %}
