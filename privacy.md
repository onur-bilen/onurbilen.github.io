# Deasy Privacy Policy

**Last updated:** October 25, 2026

This policy describes how Deasy, published by Onur Bilen, handles information. Deasy is an iPhone day planner.

## Account

You sign in with Apple or Google. Firebase Authentication stores the account that signs you in. If Apple or Google provides an email address or name, Firebase may store it with that account. Deasy shows the first name from the Apple or Google profile and does not show the email address in the app.

Removing the account in Settings deletes that sign-in. Plans, categories, completions, and saved places stored for the account are kept until you ask us to delete them. Email [onurbilen@gmail.com](mailto:onurbilen@gmail.com) to request that deletion.

## Plans and saved places

Plans, notes, categories, completion history, and saved places are stored in Google Cloud Firestore under your account. A saved place includes the name you give it, its address when one is available, and its coordinates.

A paired Apple Watch can receive plan titles and times so you can view, complete, or snooze them on the watch. That exchange stays between your iPhone and your watch.

## Voice

If you dictate a plan, the iPhone microphone and Apple’s speech recognition convert speech to text. Apple may process that audio under its own terms. Deasy parses the text on the device. Deasy does not send the recording or the transcript to Mixpanel, and it does not store the recording.

## Location

Location is used for three things:

- The day’s weather. An approximate position is sent to Open-Meteo to request the forecast. Deasy does not keep a location history.
- Centering the map when you save a place.
- Arrival reminders. If a plan is tied to a saved place, iOS can notify you within about 1 km of that place, including while Deasy is closed. That uses region monitoring, not continuous tracking, and needs the Always location permission.

Saved-place coordinates are stored with the place, as described above. Deasy does not sell location data.

## Calendar

If you allow calendar access, Deasy can write its events to a calendar on your iPhone and read calendars to notice when a linked event was deleted. Calendar content is not uploaded to a Deasy server.

## Notifications

Reminders are scheduled on the device. Notification permission is optional. Without it, alerts do not appear.

## Purchases

Deasy Pro is sold by Apple through the App Store. Apple processes the payment. RevenueCat receives your Firebase user id and the subscription status so the app can tell whether Pro is active. Deasy does not receive your card number.

## Analytics

Deasy uses Mixpanel to understand product use. Events include opening the app, opening the assistant, adding a task or event, completing a task, opening the paywall, becoming Pro, and connecting a calendar. Mixpanel also receives automatic session information such as app version and device type. The Mixpanel profile is tied to the Firebase user id and stores whether the plan is Pro or free.

Deasy does not send plan titles, notes, speech, email addresses, or location coordinates to Mixpanel.

## What we do not do

Deasy does not sell personal information. Deasy does not use your plans or speech to train a model.

## Children

Deasy is not directed at children under 13.

## Contact

Privacy questions and deletion requests: [onurbilen@gmail.com](mailto:onurbilen@gmail.com).

Apple’s and Google’s processing of sign-in, speech, maps, and payments is covered by their own policies.
