This program uses a bunch of tools to summarise youtube videos. This can be a really cool 
project if I spend some more time with it and that's my plan actually.
So in this project, I use python libraries to download a youtube video and extract the sound into 
an .mp3 format. After that, depending on the length of the .mp3 file, it divides it into chunks and this 
chunks are fed to OpenAI's whisper API (speech to text), which transcribes the audio as clearly as possible.
The transcribed audio is then given to ChatGPT with fixed prompts to summarise the text as much as it can. Upon
runnning the code, this program will give you a long summary of the video as well as a really short two liner summary.
It might have some bugs where the video doesn't download on the first try but does on the second try. This is a problem
with the library I'm using. Apart from that, all's good.
Thanks for checking it out!!!
