# jenny-tts-dataset
A high-quality, varied ~30hr voice dataset suitable for training a TTS model.

Voice is recorded by Jenny. She's Irish.

Material read include:
- Newspaper headlines
- Transcripts of various Youtube videos
- About 2/3 of the book '1984'
- Some of the book 'Little Women'
- Wikipedia articles, different topics (philosophy, history, science)
- Recipes
- Reddit comments
- Song lyrics, including rap lyrics
- Transcripts to the show 'Friends'

Total is.. 22419 prompts, files look like this:

0.txt (prompt text)
0.wav (audio)
1.txt
1.wav
2.txt
2.wav 
etc.

Audio files are 48khz, 16-bit PCM files, 2 Channels (a single microphone was used.. hmm).

# Download link: https://www.languagereactor.com/dataset.tar.zst
(link will probably change at a later date)

There was some light preprocessing done when the text was taken from the raw sources. A breakdown of where different material starts and ends can be reconstructed. Further information to follow.

# Important
The audiofiles are raw from the microphone, not trimmed. In some cases there are a few seconds of silence, sometimes a light 'knock' is audible at the beginning of the clip, where Jenny was hitting the start key. These issues will need to be addressed before training a TTS model. I'm a bit short on time these days, help welcome.

License - Attribution is required in software/websites/projects/interfaces (including voice interfaces) that generate audio using this dataset. The voice must be referred to as "Jenny", and where practical, "Jenny (Dioco)". Attribution is not required when distributing the generated clips (although welcome). Commercial use is permitted. Don't do unfair things like claim the dataset is your own. No further restrictions apply.

Jenny is available to produce further recordings for your own use. Mail dioco@dioco.io
