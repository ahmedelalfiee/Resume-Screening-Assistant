# Resume Screening Assistant
💡 Ever found yourself endlessly scrolling through job postings, thinking... "Do I even fit this role?"

That was me today, stuck in the usual cycle of reading and rereading job descriptions, trying to figure out if my resume is suitable for the job.

So, I decided to automate the process! I built a simple **Resume Screening Assistant** that does the heavy lifting for you:

✨ What it does:

1️⃣ Highlights your strengths and weaknesses in relation to a job description.

2️⃣ Gives you a match percentage, so you know exactly how well your resume aligns with the role.

It’s a simple tool that made my search easier, and I believe it could help you too, which is why I’m sharing it.

If you’re hunting for your next job and want to save time while having a bit of fun along the way, give it a try! 🚀

## Folder Structure
```text
Resume-Screening-Assistant/
├── app.py              # Streamlit UI
├── .streamlit/
│   └── config.toml     # UI Design          
├── packages.txt        # install Poppler’s binaries
├── requirements.txt
└── README.md
```

# Usage
```
- conda create -p venv python==3.10
- conda activate venv/
- pip install -r requirements.txt
- streamlit run app.py
```

**Note**: Don't forget to add your Google API key to get started with the model. 
