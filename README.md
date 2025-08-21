# Medical-chatbot

#how to run?



### steps:

```bash
Clone Repository
Project repo: https://github.com/NithiCreate/Medical-chatbot.git
cd Medical-chatbot
```

### create conda environment after opening repository
```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### install the requirements
```bash
pip install -r requirements.txt
```

### setup environment variables
GEMINI_API_KEY=your_gemini_api_key
PINECONE_API_KEY=your_pinecone_api_key

### run the app
```bash
python app.py
```

Open in browser: http://127.0.0.1:8080


###techstack used:

- Python 3.10
- LangChain
- Flask
- Generative AI
- Pinecone