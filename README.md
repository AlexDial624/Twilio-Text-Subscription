# Twilio-Text-Subscription
Twilio application that manages a subscription-based text service for the Effective Altruism at UT Austin student group (think Remind but better).

**The Why**

Org marketing commonly works as follows: Someone fills out a form at a scans a QR code, it takes them to either a) a website or b) a form. Though a website gives them more detailed info, the likely outcome is they forget about the org and the org has no way to contact them so no impact. A form 

![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/81396f8d-c1ce-4427-92a9-7a9514ca903b)

Scanning the QR code prompts a "Text +1..." popup
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/cf04a207-b9da-40a9-a76b-5a2cb22eb4b7)

Tapping that popup shows the text preview
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/4f545cc5-fba0-41d7-a91b-0e8d7bc1b03d)

Clicking Send on that sends a text. Within 60s, the user receives the defined signup text (easily changeable)
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/4f9e040d-2d52-4dab-882c-77bbca08455b)
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/0668914a-55b8-4bba-9700-89e6304880e2)

For future messages, authenticated numbers can text Broadcast [insert message here] and after confirming the content is as desired, this will be broadcasted out to all registered signups
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/12b6bf3c-7245-46d1-b564-9790a89160e1)
![image](https://github.com/AlexDial624/Twilio-Text-Subscription/assets/29134239/21dc2677-fb20-4df1-ab4a-58db6ba0c8b2)

