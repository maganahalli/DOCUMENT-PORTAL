# Create Virtual environment
pyenv virtualenv 3.10  document-portal  
# Activate the environment  
pyenv activate document-portal

# Initialize Git repo 
git init
# Commit initial 


# Install requirements.txt
pip install -r requirements.txt

# minimum requirement for this project
# LLM Model ## groq(freely), openai(paid), gemini(15days free accesss), claude(paid), huggingface(freely),ollama(local setup)

# Embedding model ## openai, hf, gemini

# vectordatabase ##inmemory ##ondisk ##cloudbased