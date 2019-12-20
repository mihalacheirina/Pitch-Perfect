# Pitch-Perfect
This is my first Udacity iOS Developer project. This iPhone app allows users to record their voice and then modulate the recorded audio to sound like a Chipmunk or Darth Vader. This app will also let the user speed up or slow down the rate of playback, and experience fun echo and reverb effects.

iOS Developer Nano Degree Project

The Pitch Perfect app is result of Intro to iOS App Development with Swift lesson of Udacity's iOS Developer Nanodegree course.

The App allows users to Record a sound using the Device’s Microphone. It then Allows Users to Play the Recorded Sound back with six different Sound Modulations: Chipmunk, Darth Vader, Slow, Fast with Reverb and Echo effect.

Pitch Perfect has two Scenes:

RecordSoundsViewController : consists a record button with a microphone image. Tapping this microphone button starts an audio recording session and present a stop button. When the stop button is clicked, the app completes recording and then show the PlaySound controller.
PlaySoundsViewController : contains six buttons to play the recorded sound file with different effects related to the button image and a stop button at the bottom
The App supports both orientations. I have varied traits for the landscape orientation of PlaySoundsViewController to make it look good with the use of stack views. App also gives a nice Pop Animation when ever we change the orientation.

The application uses code from AVFoundation to record sounds from the microphone (AVAudioRecorder) and play recorded audio with effects (AVAudioPlayer, AVAudioEngine).
