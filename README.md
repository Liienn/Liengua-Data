<p align="center">
  <img src="https://github.com/user-attachments/assets/cc420553-e77c-41ed-8b31-9f9ec1bc4079" alt="Liengua app screenshot">
</p>

# Liengua – Language Learning App
An Android app created for personal use, but shared here because why not?

It focuses on phrase-based learning using a growing collection of multilingual entries, called **Dictionary entries**, with flexible ways to practice and review them.

> [!IMPORTANT]
> An internet connection is needed to fetch Dictionary entries from this repo while using the app.
> 
> Without an internet connection:
> - only entries in 'Favorites' and 'Collections' can be viewed
> - only the 'Target practice' exercise can be used

## TTS Integration

Native Android Text-To-Speech engine used for playing phrase audio.

> [!TIP]
> To access voices like Flemish, set your device's preferred TTS engine to Google Text-to-Speech in your phone's settings.

## Supported languages
- Dutch/Flemish
- Russian
- Spanish

The app interface is in English. Dictionary entries contain translations and alternative phrasings in the languages above.

> [!NOTE]
> The translations are not perfect at all!
> 
> Especially the Spanish ones are prone to errors since these don't really get checked.
> 
> If you have suggestions for improvements in any language, feel free to use [the Feedback feature!](#send-feedback-for-an-entry) 

## Home page
The Home page houses a list of all Dictionary entries.

<p align="center">
  <img src="https://github.com/user-attachments/assets/59ce19ce-db1d-47c2-9a50-1604ddf5b057" alt="Home page screenshot">
</p>

### Dictionary entry
A Dictionary entry usually looks like this:

![image](https://github.com/user-attachments/assets/d91a603a-534b-4528-8053-7949642b20a3)

There are shortcut buttons to: 
- add it to a collection (bookmark icon)
- add it to favorites (star icon)
- open more options (three dots icon)

Clicking on a phrase will open a dialog that will show alternative phrases (if available) with the option to listen to the sentences:

![image](https://github.com/user-attachments/assets/a68c78ff-4799-4f12-bdf6-d17aed2ff164)

#### Send feedback for an entry
It is possible to send feedback for an entry if you do not agree with it, or if you want to suggest another translation to it.

Clicking the three dots icon on an entry will give you the option to send feedback for that specific phrase.
<p align="center">
  <img src="https://github.com/user-attachments/assets/8a82a341-3b8c-4747-bf0e-ef2c84bf4fa0" alt="More options opened screenshot">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/b51cfbfa-338e-4a6e-b7fc-b6757070a9e1" alt="Feedback page screenshot">
  <img src="https://github.com/user-attachments/assets/9583107f-2b61-472d-ba83-deaacad5ee36" alt="Feedback page screenshot">
</p>

> [!NOTE]
> The feedback will appear in a Google spreadsheet that I will check whenever I remember to do so. Usually about once a week.

## Menu 
Clicking the menu icon reveals the following options: 
![image](https://github.com/user-attachments/assets/5d386bde-f3ea-4e55-ac7c-9d312b12b206)

<p align="center">
  <img src="https://github.com/user-attachments/assets/a318030d-6c15-4d85-8011-076c5c31ef67" alt="Menu screenshot">
</p>

## Favorites
You can mark Dictionary entries as favorites for quick access. These aren't tied to your learning progress — just a way to save what you like.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2ff9ea54-6f90-4864-a21a-0c10484332b3" alt="Favorites page screenshot">
</p>

## Collections
### Personal Practise collection
This smart collection gathers entries where you made mistakes in exercises.

Each entry gets a weight that increases with repeated mistakes and decreases as you improve.

It is also possible to add entries manually. These will NOT get a weight when added manually (unless you make mistakes later on).
> [!NOTE]
> Automatically added entries **cannot** be removed manually.
> The automatically added entries will be removed when their weight is reduced enough.
> You’ll have to earn its removal by practicing. No shortcuts :D

### Custom collections
Create your own collections and add entries freely. Entries can belong to different collections.

Collections have:
- Collection name
- Description (optional)
- Color tag (optional)

<p align="center">
  <img src="https://github.com/user-attachments/assets/1d09b59d-1bbb-4d24-822a-59b8c650d6db" alt="Collections page screenshot">
</p>

## Exercises
The exercises will get active when you have selected the desired language to practise:
<p align="center">
  <img src="https://github.com/user-attachments/assets/fdc20b96-3dc9-4589-9417-3f0aeb933e1f" alt="Exercises page screenshot">
</p>


### Phrase matching
Match ALL the phrases available... or untill you get really really tired.

The TTS can be disabled and enabled with: ![image](https://github.com/user-attachments/assets/0361db20-694f-4bac-9702-55555645edde)
<p align="center">
  <img src="https://github.com/user-attachments/assets/0b563336-5f71-4bbc-bbb5-0d1c535c476b" alt="Phrase matching screenshot">
</p>


### Listening practice
Listen to a phrase and tap the correct words to build it.

You can replay the phrase at full speed or slower speed.
<p align="center">
  <img src="https://github.com/user-attachments/assets/39c5babd-e377-449e-afa0-b74cee46f736" alt="Listening practice screenshot">
</p>


### Target practice
Randomly start an exercise of the types mentioned above, but only uses the entries in the Personal Practice collection.


### Phrase safari
Phrases appear on the screen like creatures in the wild. Investigate them to rate (WIP), listen, or add them to a collection.

Pauses spawning while a card is open for full attention.
<p align="center">
  <img src="https://github.com/user-attachments/assets/62fd4993-d4a2-466e-a560-95edfd11381b" alt="Phrase safari screenshot">
  <img src="https://github.com/user-attachments/assets/2d5ac3e4-8cdd-4d9d-8b2a-ae28044cbfa2" alt="Phrase safari screenshot">
</p>

## Settings
Customize UI settings, check for updates and reset app data.

(Currently minimal – more settings may be added later.)
<p align="center">
  <img src="https://github.com/user-attachments/assets/76cef3c8-44d6-4264-a678-7ab07d35fa7f" alt="Settings page screenshot">
</p>

## About
Info about the app and some of your stats.
<p align="center">
  <img src="https://github.com/user-attachments/assets/5a32dde6-d9f9-4bfe-91de-6fa21c5ab6e9" alt="About page screenshot">
</p>

