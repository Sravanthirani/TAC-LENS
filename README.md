#TAC-LENS
# 📄 Terms and Conditions Summarizer 🤯

*Cut through the legal jargon with ease.*

The *Terms and Conditions Summarizer* is a powerful tool that simplifies complex legal documents into clear, easy-to-understand summaries. Whether you're reviewing user agreements, privacy policies, or service terms, this tool helps you get the gist in seconds.

---

## 🚀 Features

- ✅ Summarize lengthy legal documents instantly  
- ✅ Ideal for business owners, legal professionals, and everyday users  
- 🧠 Powered by *LLama 3 70B* via the *Gorq API*  
- ⚡ Fast, accurate, and AI-driven summaries  
- 🔒 Understand what you’re agreeing to before clicking “Accept”

---

## 😁 Get Started in Minutes

### 🔌 Plugin Installation Instructions

1. *Download & Extract* the plugin folder  
2. Open *Google Chrome*  
3. Click the *three dots* in the top-right corner  
4. Go to *More Tools > Extensions*  
5. Enable *Developer Mode* (top right toggle)  
6. Click *Load Unpacked*  
7. Select the *extracted plugin folder*  

That’s it! Your summarizer is now ready to go.

---

### 🔐 Add Your Groq API Key

Before using the summarizer, you need to add your **Groq API key**:

1. Open the plugin folder you extracted.
2. Navigate to the file:  
   ```
   /script.js
   ```
3. You’ll see something like:
   ```js
   const apikey = "YOUR_API_KEY_HERE";
   ```
4. Replace `"YOUR_API_KEY_HERE"` with your actual Groq API key:
   ```js
   const GROQ_API_KEY = "sk-xxxxxx..."; // your real key
   ```
5. **Save** the file.
6. Go back to `chrome://extensions`, and click **Reload** on the plugin.

> ⚠️ **Note:** Never share your API key publicly or commit it to GitHub.

---

## 💡 Use Cases

- Reviewing privacy policies before signing up for new services  
- Checking app terms before downloading  
- Understanding the fine print in digital contracts  
- Saving time and reducing risk in business workflows  

---

## 🧠 Technology Stack

- *Gorq API*
- *LLama 3 70B* (state-of-the-art language model)
- *JavaScript / HTML / CSS* for the plugin interface

---

## 🙌 Contribute

Found a bug or want to suggest a feature? Feel free to open an issue or pull request. All contributions are welcome!

---

## 📜 License

MIT License – use it freely and responsibly.

---
