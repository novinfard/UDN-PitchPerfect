# Pitch Perfect
The Pitch Perfect app allows users to record a sound using the device's microphone. It then allows users to play the recorded sound back with six different sound modulations.

## Sound modulations
- Super Slow
- Super Fast
- Chipmunk
- Darth Vader
- Parrot (Echo effect)
- Reverb

## Screenshots
|  Start to record |  While Recording |  Playback by SoundEffect |
| :------------: | :------------: | :------------: |
|  [![](http://www.novinfard.com/media/gitshots/uda-perfectpitch-1.png)](http://www.novinfard.com/media/gitshots/uda-perfectpitch-1.png) |  [![](http://www.novinfard.com/media/gitshots/uda-perfectpitch-2.png)](http://www.novinfard.com/media/gitshots/uda-perfectpitch-2.png) |  [![](http://www.novinfard.com/media/gitshots/uda-perfectpitch-3.png)](http://www.novinfard.com/media/gitshots/uda-perfectpitch-3.png)|

## Implementation
The app has two view controller scenes:

- **RecordSoundsViewController** - consists a record button with a microphone image. Tapping this microphone button 
starts an audio recording session and present a stop button. When the stop button is clicked, the app completes recording and then show the PlaySound controller.

- **PlaySoundsViewController** - contains six buttons to play the recorded sound file with different effects and a button to stop the playback.

The application uses code from `AVFoundation` to record sounds from the microphone (`AVAudioRecorder`) and play recorded audio with effects (`AVAudioPlayer`, `AVAudioEngine`).

## Main Targets
AVFoundation, UIKit, Stack Views, Auto Layout

## Credits
The concept for this app was presented during the iOS Nanodegree programme provided by Udacity.

## Author
**Soheil Novinfard** - [www.novinfard.com](https://www.novinfard.com)

## License
This project is licensed under the MIT License.