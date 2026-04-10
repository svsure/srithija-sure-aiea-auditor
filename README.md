# xai-neuron-explanations
## Neuron Explanations for LLMs

### Week 2 Deliverable
<ins>Task: Setting Up the Environment</ins>
* Issue: ModuleNotFoundError: No module named “onmt”
  Solution: installed OpenNMT using pip install OpenNMT-py
* Issue: AttributeError: module 'pyparsing' has no attribute 'operatorPrecedence'
  Solution: Downgraded pyparsing to version 2.4.7 using pip install pyparsing==2.4.7
* Issue: ModuleNotFoundError: No module named 'spacy'
  Solution: Installed spaCy using pip install spacy and downloaded language model using python -m spacy download en_core_web_sm
* Issue: Missing required dataset files 
  Solution: Attempted to locate/generate data, but repo does not provide preprocessing instructions or files
* Issue: FileNotFoundError: data/analysis/snli_1.0_dev.vec
  Description: The script requires a pretrained model checkpoint.
  Solution: Identified that the model has to be downloaded separately based on the documentaiton. 

<ins>Remaining tasks:</ins>
* Download the pretrained model
* Complete the Neurons list

I will complete these tasks soon! I apologize for the delay as this is new material to me.

<ins>Workstation Setup</ins>
Macbook Pro (14-inch, 2024)
CPU: Apple M4 Pro
GPU: Integrated Apple GPU
Memory (RAM): 24 GB
OS: macOS Tahoe (version 26.3)


