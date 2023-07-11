# Youtube-Video-Summarizer

A chrome extension to summarize long YouTube videos by utilizing YouTube's transcript feature.

## Requirements
- The following Python modules must be installed to run the API
  - ```flask```
  - ```youtube-transcript-api```
  - ```transformers```

 ## Commands to install APIs
 - flask - ```python -m pip install flask```
 - youtube-transcript-api - ```pip install youtube-transcript-api```
 - transformers - ```pip install transformers datasets evaluate rouge_score```

## Instructions
- Run ```app.py``` to start the summarizer API.
- Load the custom extension into any Chromium browser.
- Go to any YouTube video and click the extension logo to summarize.
