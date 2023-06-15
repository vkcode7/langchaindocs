# Leveraging Your Own Documents in a Langchain Pipeline
This project highlights how to leverage a ChromaDB vectorstore in a Langchain pipeline to create *drumroll please* a GPT Investment Banker (ergh, I cringed as I wrote that, but alas it's actually pretty practical). You can load in a pdf based document and use it alongside an LLM without the need for fine tuning. 

# Startup 🚀
1. Create a virtual environment `python -m venv langchainenv`
2. Activate it: 
   - Windows:`.\langchainenv\Scripts\activate`
   - Mac: `source langchainenv/bin/activate`
   - Deactivate: conda deactivate
3. Clone this repo `git clone https://github.com/nicknochnack/LangchainDocuments`
4. Go into the directory `cd LangchainDocuments`
5. Install the required dependencies `pip install -r requirements.txt`
6. Add your OpenAI APIKey to line 22 of `app.py`
7. Start the app `streamlit run app.py` 

# Other References 🔗
<p>The main LG Agent used:<a href="https://python.langchain.com/en/latest/modules/agents/toolkits/examples/vectorstore.html">Langchain VectorStore Agents
</a></p>

# GIT
git init
git add *.*
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/vkcode7/langchaindocs.git
git push -u origin main
