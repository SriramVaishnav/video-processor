A simple yet powerful Node.js server that

- Receives data packets as chunks from the client using a secure socket connection
- Process the chunks and saves as a video file
- Saves the video file in a AWS S3
- Then forwards the video to OpenAI's Whisper that generates transcript for the video
