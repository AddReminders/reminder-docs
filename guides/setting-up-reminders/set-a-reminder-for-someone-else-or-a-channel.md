# Set a reminder for someone else or a channel

You can ask the Reminder Bot to remind an entire channel or multiple users on your behalf about some task. Again, here there are 2 ways to achieve this

### Option 1: Using /remind slashcommand

1. Goto any Rocket.Chat channel or Direct message and type `/remind` or `/remind create` from the message input field.
2. Enter the basic reminder info like date, time and reminder message.
3. Click on **More Options**
4. Under **Who to remind?** input field, select **Channel(s)** or **User(s)**
5. Enter the channels or user details appropriately. Separate them with a comma if you wish to remind multiple channels or users.
   1. If you wish to remind users, then enter their **usernames**
   2. If you wish to remind channels, then enter the respective **channel name**
6. Finally, Click on **Create**

{% hint style="info" %}
**Tip:** Type /remind #general #random from the message input box to use the auto-complete feature.
{% endhint %}

{% embed url="https://www.loom.com/share/694d2771e4134217995b1edf6f77a38b" %}
Create a reminder for a channel in Rocket.Chat
{% endembed %}



### Option 2: Using Message Input Action Button

{% hint style="info" %}
Available on Version 2.0.0 and above
{% endhint %}

1. Goto any Rocket.Chat channel or Direct message where you wish to send a reminder and click on the Plus Icon in the message input field on the bottom right - then click on **Add Reminders**
2. Fill in the reminder information like Date, Time and a short description of what you'd like to remind your audience about, and then click on **Create**.

{% embed url="https://www.loom.com/share/a5ecfebf787f4df7b1da2d1928c7b5f8" %}
Create a reminder for a channel using Message Input Action Button
{% endembed %}

{% embed url="https://www.loom.com/share/93918a3625af4462bb29a06624941afa" %}
Create reminders for user(s) using Message Input Action Button
{% endembed %}

### Reminder Notification

In the case of **Channel** reminders, the Reminder bot will send a message immediately to these channel(s), letting them know this reminder is coming up. And then when the reminder is due, the reminder bot will send out the actual reminder message at the specified time.

![Channel Reminder Notifications](<../../.gitbook/assets/image (29).png>)

On the other hand, in the case of **User** reminders, the reminder bot will only send out a reminder to the target users, when the reminder is due via a Direct Message.

![User Reminder Notification](<../../.gitbook/assets/image (5).png>)
