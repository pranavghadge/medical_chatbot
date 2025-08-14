# Medical ChatBot Using LLM 🧠, LangChain 🦜, Pinecone ⚛

### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone
- RAG

### FLOWCHART:
<p align="center">
  <img src="https://github.com/pranavghadge/medical_chatbot/blob/main/FlowChart.png" height="900" width="1000"/>
</p>

## How to run?
### STEPS:

Clone the repository

```bash
git clone https://github.com/pranavghadge/medical_chatbot.git
```
### Step 1- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```


### Step 02- Install the Requirements
```bash
pip install -r requirements.txt
```
### Create a `.env` file in the root directory and add your Pinecone & OpenAI credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

Run the following command to store embeddings to Pinecone
```bash
python store_index.py
```

Finally run the following command
```bash
python app.py
```

Now,
```bash
Open Up -> localhost:
```

Read more at: 
https://code2tutorial.com/tutorial/64e51063-1577-4e3f-a1c3-c9e9b5f9138f/index.md
