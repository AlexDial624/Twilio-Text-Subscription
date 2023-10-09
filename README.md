# Twilio-Text-Subscription
Twilio application that manages a subscription-based text service for the Effective Altruism at UT Austin student group (think Remind but better).

**The Why**

Org marketing commonly works as follows: Someone fills out a form at a scans a QR code, it takes them to either a) a website or b) a form. The benefit of a form is now you can contact the interested member, but perhaps the friction of a form loses you some potentially interested members. A QR code to Text setup though improves on this in several ways.

The benefits of this Twilio setup, as opposed to other marketing techniques, are:
 • Minimal friction, user simply scans & clicks send
 • They can imminently see more info about the org & next event
 • The org has an easy way to reach out after the interaction
 • Broadcasting messages over text rather than email won't get lost in spam
 • People can write back easily 

Basically, this combines the best of email form signups with the best of direct link to website/linktree.
 

Scanning the QR code prompts a "Text +1..." popup. Tapping that popup shows the text preview
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/42c59c84-b3ca-4563-9327-bd06655a619b)

Clicking Send on that sends a text. Within 60s, the user receives the defined signup text (easily changeable)
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/d8243460-2e77-4e9b-936e-28c22b88ada5)


For future messages, authenticated numbers can text Broadcast [insert message here] and after confirming the content is as desired, this will be broadcasted out to all registered signups
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/147d5fd1-4ecb-48af-b401-d46a9e721c47)

In Twilio, this is managed through a studio flow, with custom functions and data stored in a Twilio data map.
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/81396f8d-c1ce-4427-92a9-7a9514ca903b)
