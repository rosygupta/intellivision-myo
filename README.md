# intellivision-myo
Live augumented reality using google glass and clarifai api, smoothly controlling it with Myo armband.

We came up with a weekend hardware hack at Spartahacks 2016, Michigan State University.

Harware : Google glass, Myo armband
API : Clarifai
Backend : Firebase

Firebase is used as our cloud storage and analytics platform to get insights of the personalised data. All the tags from Clariifai are stored in Firebase.

There are two implementations of the Clarifai Api 
  
  * Android Device : camera-tagger
  * Google Glass : glass-camera-tagger

