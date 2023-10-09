# Twilio-Text-Subscription
Twilio application that manages a subscription-based text service for the Effective Altruism at UT Austin student group (think Remind but better).

**The Why**

Org marketing commonly works as follows: Someone fills out a form at a scans a QR code, it takes them to either a) a website or b) a form. Though a website gives them more detailed info, the likely outcome is they forget about the org and the org has no way to contact them so no impact. A form 

![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/81396f8d-c1ce-4427-92a9-7a9514ca903b)

Scanning the QR code prompts a "Text +1..." popup. Tapping that popup shows the text preview
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/42c59c84-b3ca-4563-9327-bd06655a619b)

Clicking Send on that sends a text. Within 60s, the user receives the defined signup text (easily changeable)
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/d8243460-2e77-4e9b-936e-28c22b88ada5)


For future messages, authenticated numbers can text Broadcast [insert message here] and after confirming the content is as desired, this will be broadcasted out to all registered signups
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/12b6bf3c-7245-46d1-b564-9790a89160e1)
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/21dc2677-fb20-4df1-ab4a-58db6ba0c8b2)

