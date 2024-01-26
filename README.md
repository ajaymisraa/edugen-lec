# EduGen Scribe: Automate Lecture Notes

Input a video, recording, or even just a recording from your phone of a lecture. Like magic, a detailed note sheet will be made in LaTeX! 

## Details 

Fine tuned GPT-4 Vision (preview) and in-house solution to intake lecture video and audio and produce coherent and informative LaTeX notes. Pre-trained specifically for Duke’s intermediate mathematics and computer science courses.

Works through the pipeline: 
- Transcribe audio to text. 
- Use a model to shorten the video by finding the lecture's "key moments." Nothing is lost in this stage due to audio transcription backing up information. 
- Break off audio and corresponding video into smaller "chunks" and pass them through a fine-tuned model of GPT-4. 
- Using the resulting information, pass the simulated "notes" into in-house notes to the LaTeX transcription model.

Open source code expected in February 2024.
