# YouTube Video Transcript Summarizer with Generative AI

**Introduction**

A tool that saves you time by turning long YouTube video transcripts into short, clear summaries. It pulls the transcript directly from YouTube, then uses Google's Gemini AI to condense it into the key points — so you can get the gist of a video without watching the whole thing. Built with Streamlit for a simple, clean interface.

<br />

**Table of Contents**

1. Key Technologies and Skills
2. Installation
3. Usage
4. Features
5. Contributing
6. License
7. Contact

<br />

**Key Technologies and Skills**
- Python
- Google Generative AI
- YouTube Transcript API
- Prompt Engineering
- Streamlit

<br />

**Installation**

To run this project, install the following packages:

```python
pip install python-dotenv
pip install streamlit
pip install streamlit-extras
pip install youtube-transcript-api
pip install google-generativeai
pip install langcodes
pip install language_data
```

<br />

**Usage**

To use this project, follow these steps:

1. Clone the repository: `git clone <YOUR_REPO_URL_HERE>`
2. Install the required packages: `pip install -r requirements.txt`
3. Add your Google API key to the `.env` file.
4. Run the Streamlit app: `streamlit run app.py`
5. Access the app in your browser at `http://localhost:8501`

<br />

**Features**

#### YouTube Video Transcript Retrieval

- **Input Video Link:** Paste a YouTube video link and the app automatically extracts the video ID and prepares the transcript request.
- **Transcript Language Detection:** Detects all available transcript languages for the given video, so you can pick the one you want.
- **Language Conversion:** Language codes are converted into readable names, making it easy to choose the right transcript.

#### Transcript Processing

- **Language Selection:** Retrieves the transcript in your chosen language.
- **Transcript Handling:** Cleans and formats the transcript so it's ready for accurate AI summarization.

#### AI-Powered Summarization

- **Generative AI Model:** Uses Google's Gemini AI to generate concise, context-aware summaries from the transcript and a purpose-built prompt.
- **Custom Prompting:** A carefully designed prompt keeps summaries focused on the actual key points of the video.

#### Streamlit Application

- **User-Friendly Interface:** Input links, pick a language, and read the summary — all from one clean screen.
- **Real-Time Interaction:** Summaries generate and display almost instantly.

#### References

- Streamlit: [https://docs.streamlit.io/](https://docs.streamlit.io/)
- Google Gemini AI: [https://ai.google.dev/](https://ai.google.dev/)
- YouTube Transcript API: [https://pypi.org/project/youtube-transcript-api/](https://pypi.org/project/youtube-transcript-api/)
- Langcodes: [https://pypi.org/project/langcodes/](https://pypi.org/project/langcodes/)

<br />

**Contributing**

Contributions are welcome! If you run into issues or have ideas for improvements, feel free to open a pull request.

<br />

**License**

This project is licensed under the MIT License. See the LICENSE file for details.

<br />

**Contact**

📧 Email: gowdapunith1728@gmail.com

Feel free to reach out with any questions.
