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
* Issue: Missing required dataset files (snli_1.0_dev.vec not included in repo)
  Solution: Attempted to locate/generate data, but repo does not provide preprocessing instructions or files
* Issue: FileNotFoundError: data/analysis/snli_1.0_dev.vec
  Description: The script requires a preprocessed vector file that is not included in the repository. The repository also does not provide clear       instructions or scripts to generate this file.
  Solution: Attempted to locate or generate the dataset, but due to missing preprocessing pipeline and incomplete documentation, the file could not be created. Proceeded with analysis based on understanding of the system.

<ins>Remaining tasks:</ins>
Download the pretrained model
Complete the Neurons list

I will complete these tasks hopefully by Sunday! I apologize for the delay as this is new material to me.

<ins>Workstation Setup</ins>
Macbook Pro (14-inch, 2024)
CPU: Apple M4 Pro
GPU: Integrated Apple GPU
Memory (RAM): 24 GB
OS: macOS Tahoe (version 26.3)


