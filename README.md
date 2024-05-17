# Youtube-Transcript-Summarizer
YouTube Transcript Summarizer This project is a YouTube Transcript Summarizer that automates the process of extracting audio from a YouTube video, transcribing the audio to text, and summarizing the transcribed text. The project leverages various libraries and models, including PyTube, FFmpeg, librosa, Hugging Face's huggingsound, and transformers.

Usage  
Here's how you can use the YouTube Transcript Summarizer:    

Clone the repository to your local machine.  
Navigate to the project directory.  
Run the script with the desired YouTube video URL.  


Dependencies  
This project requires the following libraries and tools:  

PyTube  
FFmpeg  
librosa  
soundfile  
Hugging Face huggingsound  
Hugging Face transformers  

Code Explanation  
Downloading Audio  
The script uses PyTube to download the audio from a YouTube video.  
Audio Conversion  
The downloaded audio is converted to WAV format using FFmpeg.  
Audio Chunking  
To handle large audio files and avoid memory issues, the audio is chunked into smaller pieces using librosa.  
Audio Transcription  
The audio chunks are transcribed to text using Hugging Face's huggingsound library.  
Text Summarization  
The transcribed text is summarized using Hugging Face's transformers library.  
