# Shipyard-Jinsei.ai
Various data transformation and validation solutions powered by TF and GPT. 

## 1) XML/CSV Sequence-to-Sequence Sheets Transformer 

- excel sheet content to database mapping service 
- needs investment statements sets from compatible and not compatible excel sheets 


Shipyard Similar Systems: 

Optimized Areas In Use Case: 

### Service Interface/DevOps

Shipyard container routing, REST transfer protocol preference.  

### Service StartUp: Set Env & Run Models

Boilerplate Sequence to Sequence model: https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/xmlSeq2Seq.py

edit this

startup:
Navigate to the directory where you want to create the virtual environment
```linux
# cd (project root) 
```
Create a virtual environment (you can choose any name, here we use "venv")
```linux
python3 -m venv venv
```

Activate the virtual environment
```linux
source venv/bin/activate
```

Install required packages
```linux
pip install numpy TFANN matplotlib scikit-learn tensorflow
```

Make sure you are in the directory containing your script
```linux
cd (rn the csv and the py file are in Machine)
```
Run the script
```linux
python chat3deriv.py
```

Training Data ReadMe: https://

```python
# Training data organization
training_data = [
    {"input_xml": "<input_xml_1>", "target_xml": "<target_xml_1>"},
    {"input_xml": "<input_xml_2>", "target_xml": "<target_xml_2>"},
    # Add more examples as needed
]

# Extract input and target sequences from training data
input_xml_data = [example["input_xml"] for example in training_data]
target_xml_data = [example["target_xml"] for example in training_data]

```

## 2) Chat GPT + XML/CSV Content/Position Validation Service 

- TS Boilerplate Prompt (content) Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/server.js
- PY Boilerplate Sequence 2 Sequence Training: https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/xmlSeq2Seq.py
- TS Boilderplate Prompt Live Matrix Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/matrixContextChatBoiler.js)

## 3) Chat GPT Database Element Extraction & Report Compilation Service

- Boilerplate Prompt (query syntax) Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/server.js
- Boilerplate Classification Training: https://github.com/PortalToBlockchainOrganization/CryptoCountAI/blob/master/typeModelResult1.py
- Integrate Shipyard DB Queries to Taxonomy Element pairings 
- Needs collections of reports required by Shipyard clientele 


