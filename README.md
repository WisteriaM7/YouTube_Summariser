# 🎥 YouTube Summariser

Tired of watching 30-minute YouTube videos for just 2 minutes of useful content?
**YouTube Summariser** extracts and summarizes YouTube video transcripts so you get to the point—fast.

---

## 🚀 Features

* ✅ Extracts YouTube video transcripts using video URL
* 🧐 Summarizes the content using advanced NLP techniques
* 💬 Outputs concise summaries with minimal fluff
* 🔗 Supports direct YouTube URLs
* 🔍 Great for research, study, and quick reviews

---

## 🛠️ Technologies Used

* Python 3.x
* `youtube-transcript-api` – For fetching video transcripts
* `transformers` (or `sumy`, depending on your implementation) – For text summarization
* `streamlit` (optional) – For building a simple UI

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/YouTube-Summariser.git
cd YouTube-Summariser
pip install -r requirements.txt
```

---

## ▶️ How to Use

1. Run the notebook:

   ```bash
   jupyter notebook YouTube_Summariser.ipynb
   ```

2. Paste your YouTube video URL when prompted.

3. Let the tool fetch the transcript and generate a summary!

---

## 🧪 Example

**Input:**
[https://www.youtube.com/watch?v=dQw4w9WgXcQ](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

**Output Summary:**

> In this video, the artist explores themes of loyalty, emotional vulnerability, and unexpected betrayals—set to an upbeat soundtrack that contrasts with the lyrics.

---

## 💡 Future Enhancements

* Add multi-language support
* Integrate video title and thumbnail preview
* Enable keyword-based summarization
* Build a Streamlit or Flask UI

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

Special thanks to:

* [YouTube Transcript API](https://pypi.org/project/youtube-transcript-api/)
* [HuggingFace Transformers](https://huggingface.co/)
