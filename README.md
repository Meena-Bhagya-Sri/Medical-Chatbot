# Medical-Chatbot


## Steps to run my project
 

1)Create virtual Environment
    conda create -n mchatbot python=3.8 -y
2)Activate the environment
    conda activate mchatbot
3)Create Requirements.txt and add
    ctransformers==0.2.5
    sentence-transformers==2.2.2
    pinecone-client
    langchain==0.0.225
    flask
3)install requirements.txt
    pip install -r C:\\Users\\meenu\\anaconda3\\etc\\profile.d\\Medical-Chatbot\\requirements.txt
4)Create Instruction.txt file after creating model folder and inside give instruction'
    ## Download the llama 2 model :
    llma-2-7b-chat.ggmlv3.q4_0.bin

    ## From the following link:
    https://huggingface.co/TheBloke/Llama-2-7b-Chat-GGML/tree/main
5)create trails.ipynb and import libraries needed
6)create account in vector database(pinecone) and create api key and env variables
7)Extract the data preprocess it 