# AI Assistant for Data Science

## Installation

### Cloning the Repository

    git clone https://github.com/evadelzz1/llm-PandasAI-Assistant.git

### Setting up a Virtual Environment

    cd ./llm-PandasAI-Assistant

    pyenv versions

    pyenv local 3.11.6

    echo '.env'  >> .gitignore
    echo '.venv' >> .gitignore

    echo 'OPENAI_API_KEY=sk-9jz....'    >> .env

    ls -la

### Activate the virtual environment

    python -m venv .venv && source .venv/bin/activate


### Install the required dependencies

    pip list

    pip install -r requirements.txt

    pip freeze | tee requirements.txt.detail

### Running the Application

    python -m streamlit run main.py

### Deactivate the virtual environment

    deactivate



## Reference

    # Building an AI Data Assistant with Streamlit, LangChain and OpenAI | Part 1
    # https://www.digilab.co.uk/posts/build-an-ai-data-assistant-with-streamlit-langchain-and-openai
    # https://www.youtube.com/watch?v=CBRE_Me1IQ0

    # Building an AI Data Assistant with Streamlit, LangChain and OpenAI | Part 2
    # https://www.digilab.co.uk/posts/expanding-our-ai-data-assistant-to-use-prompt-templates-and-chains
    # https://www.youtube.com/watch?v=4ChcBu0eY2Q

    # Building an AI Data Assistant with Streamlit, LangChain and OpenAI | Part 3
    # https://www.digilab.co.uk/posts/completing-our-ai-data-assistant-with-custom-knowledge-using-a-pinecone-vector-database
    # https://www.youtube.com/watch?v=dngv-D_t3YI
