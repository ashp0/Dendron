# Dendron

Dendron is a writing app for Mac and iPhone that opens and saves Scrivener projects.

## Mac

<img src="screenshots/mac/editor.png" alt="Dendron on the Mac: the binder, a chapter open in the editor, and the inspector" width="100%">

<img src="screenshots/mac/corkboard.png" alt="Dendron on the Mac: a chapter shown as index cards on the corkboard" width="100%">

## iPhone

| Library | Binder | Editor | Reading |
|:---:|:---:|:---:|:---:|
| <img src="screenshots/iphone/library.png" alt="Library of projects with sync status" width="200"> | <img src="screenshots/iphone/binder.png" alt="Binder of a novel" width="200"> | <img src="screenshots/iphone/editor.png" alt="Editing a document with the keyboard up" width="200"> | <img src="screenshots/iphone/reading.png" alt="Reading a document, with a notice of changes merged from the Mac" width="200"> |

| Footnotes | Today page | Dictation: speaking | Dictation: typed |
|:---:|:---:|:---:|:---:|
| <img src="screenshots/iphone/footnote.png" alt="A footnote opened in place" width="200"> | <img src="screenshots/iphone/today.png" alt="A new day page made from a template" width="200"> | <img src="screenshots/iphone/dictation-listening.png" alt="Recording while the phone is raised to the ear" width="200"> | <img src="screenshots/iphone/dictation-typed.png" alt="The spoken words typed at the cursor" width="200"> |

| Dictation settings | Synced | Merged | Merge report |
|:---:|:---:|:---:|:---:|
| <img src="screenshots/iphone/dictation-settings.png" alt="Dictation settings: on-device speech models" width="200"> | <img src="screenshots/iphone/sync-synced.png" alt="Sync settings after a successful sync" width="200"> | <img src="screenshots/iphone/sync-merged.png" alt="Changes from the Mac merged with the iPhone's" width="200"> | <img src="screenshots/iphone/merge-report.png" alt="Report of what the last merge changed" width="200"> |

## What's inside

- A Mac app in AppKit and an iPhone app in SwiftUI (Swift 6), on one shared Objective-C core.
- Fast on old hardware: on a 2013 Mac running OS X 10.9 it opens a million-word project in 0.6 seconds, and each keystroke lands in about 2 milliseconds. Project search and the outliner were profiled and made about three times faster.
- Mac and iPhone sync through Git. More than 3,400 automated checks cover sync, including tests that break a sync halfway. The iPhone app has 156 unit and UI tests.
- On-device dictation on iPhone (added November 2026): raise the phone to your ear, speak, lower it, and the words are typed at the cursor, transcribed on the phone by a Parakeet model. No button, no mode.
- Designed and built alone by [Ashwin Paudel](https://github.com/ashp0).

## Source and demo

The source code is private. A live demo is available on request: reach me through [github.com/ashp0](https://github.com/ashp0) or [linkedin.com/in/ashpaudel](https://www.linkedin.com/in/ashpaudel).

© 2026 Ashwin Paudel. All rights reserved.
