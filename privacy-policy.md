# π-Graph privacy policy

Last updated: 16 October 2026

π-Graph is a personal map of the people you know. This policy covers the
iPhone, Android, Mac and Windows apps.

## The short version

- π-Graph has no account, no server and no analytics. Nothing you put into it
  is ever sent to us.
- Your graph is stored on your own devices. Your phone and computer sync
  with each other directly over your own Wi-Fi, encrypted.
- One optional feature sends data out: reading a note you speak or type. It
  is off until you choose an AI service, add your own key for it, and agree
  to a screen that says what will be sent. The note then goes from your
  device straight to that service, under your own account with them.

## What is stored, and where

Everything you enter (people, sheets, connections, details, dates, events and
your own page) is stored in a database on the device you use:

- **iPhone:** in the app's own storage. If your iPhone backs up to iCloud or
  to a computer, that backup includes π-Graph's data, as it does for other
  apps. Apple keeps it under your Apple Account.
- **Android:** in the app's private storage. π-Graph opts out of Google's
  cloud backup. Moving to a new phone directly can still copy the data
  across.
- **Mac and Windows:** in the app's data folder on your computer.

**Backups.** π-Graph keeps up to 14 copies of your graph as files:

- **Mac:** in `Documents/pi-graph-backups`.
- **Windows:** in your user folder under `pi-graph-backups`.
- **iPhone:** in the app's folder in the Files app.
- **Android:** in storage private to the app.

If your computer syncs that folder to a cloud service, for example iCloud
Drive's "Desktop & Documents" or OneDrive, the backups go with it, under your
account with that service.

**Exports and saved copies** go wherever you send or save them. On Android, a
copy is also kept in `Documents › Pi-Graph`, which other apps that have full
storage access can read.

Deleting the app deletes the data it holds on that device. On iPhone and
Android this includes the backups. Copies you exported or saved elsewhere,
and backups on a computer, stay until you delete them.

## Sync between your phone and computer

When you switch sync on, your computer accepts connections on your local
network, and only while sync is on. Your phone connects to it there. The phone
only connects to private local-network addresses, never to the internet.

What the two exchange is encrypted with a key that your computer creates when
you pair them. Each device keeps the key in its own system keychain, and the
key itself is never sent over the network. No one else, including us, can read
what they exchange.

## Reading a note with an AI service (optional)

Speak and Type turn a note into changes to your graph, such as a new person,
a detail or a connection. You review the changes before anything is saved.
To do this, π-Graph sends the note to an AI service. This happens only after
you have done all three of these:

1. chosen a service under AI features: Claude (run by Anthropic), ChatGPT (run
   by OpenAI), Gemini (run by Google), or OpenRouter;
2. added your own API key for that service; and
3. said yes to a screen that names the service and lists what is sent. You
   are asked separately for each service.

**What is sent with each note:**

- the text of the note;
- today's date;
- for every person in your graph: their name, sheets, birthday, where they
  live, and the details you have added to their profile;
- every connection between two people, with its type and note.

**What is never sent:** each person's Contact field (where phone numbers,
email addresses and the like belong), special dates other than birthdays,
the events you have logged, and your own page. Anything you type into a
person's details is sent with them, so keep contact information in the
Contact field.

The request goes directly from your device to the service, using your key.
It does not pass through us, and we never see it or the reply. The service
handles what it receives under its own terms and privacy policy. Those terms
are part of your agreement with that service:

- Anthropic (Claude): [https://www.anthropic.com/legal/privacy](https://www.anthropic.com/legal/privacy)
- OpenAI (ChatGPT): [https://openai.com/policies/privacy-policy](https://openai.com/policies/privacy-policy)
- Google (Gemini): [https://ai.google.dev/gemini-api/terms](https://ai.google.dev/gemini-api/terms). Google's terms
  differ between its free and paid tiers, including on whether what you send
  may be used to improve Google's products.
- OpenRouter: [https://openrouter.ai/privacy](https://openrouter.ai/privacy). OpenRouter passes each note on
  to the company that runs the model you chose, and that company's terms
  apply too.

You can withdraw your agreement at any time under AI features. Removing your
key stops all sending.

**Your API keys** are kept in your device's system keychain (Keychain on
Apple devices, Credential Manager on Windows, the Android keystore). They are
never part of your graph, an export or a backup, and they are never sent
anywhere except to the service they belong to.

## Voice

Speak uses the speech recognition built into your device's operating system.
Depending on your device and settings, the system may send the audio to its
maker to be transcribed (to Apple, on an iPhone or Mac), under that company's
privacy policy. π-Graph receives only the text. Speak is not available on
Android, where you can type the note instead.

## Camera

On a phone, π-Graph can use the camera to read the pairing code your computer
shows. Images from the camera are read on the phone, are never saved and never
leave it. The camera is used for nothing else.

## Permissions

- **Local network** (iPhone): to sync with your computer.
- **Camera** (iPhone, Android): to scan the pairing code. This is optional;
  you can type the code instead.
- **Storage** (Android 10 and older only): to save a copy of your graph to
  Documents.

## Children

π-Graph is not directed at children under 13, and we do not knowingly hold
data about anyone, child or adult, since we hold no data at all.

## Your rights

Because we receive nothing, we hold nothing about you to access, correct,
export or delete. You can export and delete everything in the app yourself.
For a note already sent to an AI service, use that service's own controls
or contact them; their privacy policies are linked above.

## Changes

If π-Graph starts sending anything new, this policy will be updated before
that version is released, and the app will ask for your agreement again
before a note sends it.

## Contact

π-Graph is developed by Daniil Baranov. Questions about this policy:
[3.14graph@gmail.com](mailto:3.14graph@gmail.com)
