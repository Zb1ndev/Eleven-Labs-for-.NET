# ElevenLabs.NET
A C# Class that returns a .mp3 with a AI Generated voice using Eleven Labs

### Finding Voice IDs
To find Voice IDs go to : https://api.elevenlabs.io/v1/voices and search for a Voice ID

### Using the Class
To use, simply create a ElevenLabs object and in the constructer input your key, then await the RequestAudio function. 
The function will take in 3 parameters :
1. Prompt is what you want it to say
2. Voice is the VoiceID
3. fileName is the name of the file you want it to create
