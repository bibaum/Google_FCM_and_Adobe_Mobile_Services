# Example Implementation of Google Firebase Cloud Messaging (FCM) and Adobe Mobile Services Android SDK.

 * Adobe Mobile Services Android SDK 4.13.6

## Implementation Steps:
 * [Set up Firebase Cloud Messaging in Client App](https://firebase.google.com/docs/cloud-messaging/android/client)
 * [Enable Push Messages on Mobile Services Website](https://marketing.adobe.com/resources/help/en_US/mobile/configure_push_messaging.html)
 * [Add Adobe Mobile Services SDK and Core Aquisition Implementation](https://marketing.adobe.com/resources/help/en_US/mobile/android/dev_qs.html)
 * [Enable Push Messages in App](https://marketing.adobe.com/resources/help/en_US/mobile/android/push_messaging.html)


## Testing Implementation
### Test Google Firebase implemantation

 * [Send Notification Message via Firebase Console](https://firebase.google.com/docs/cloud-messaging/android/first-message#send_a_notification_message)
 * [Test Firebase API via POST request](https://firebase.google.com/docs/cloud-messaging/send-message) e.g. use Postman 

```
https://fcm.googleapis.com/fcm/send
Content-Type:application/json
Authorization:key=AIzaSyZ-1u...0GBYzPu7Udno5aA

{
	"notification": {
    	"title": "Postman message",
    	"body": "Great the API is working"
	},
	"to" : "dE_kvZs6cxc:APA91bEr2qfPnEt-mtkaxjIS1CI19YmHdv4YkAt0Mao7SZtpKfwuzoZAQHD0r..."
}
```

### Test Adobe Mobile Services Implementation
 * In Mobile Services you can the Push Service in your App Settings where you input the API key
 * [Create a Push message] (https://marketing.adobe.com/resources/help/en_US/mobile/c_experience__push_message.html) and use the Test button
