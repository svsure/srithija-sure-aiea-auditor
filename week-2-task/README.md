# Week 2 Deliverable:
(originally completed/recorded on a Google Document, transferred previous work and current work to README.md)
## Task: Setting Up the Environment
* Issue: ModuleNotFoundError: No module named “onmt”
    * Solution: installed OpenNMT using pip install OpenNMT-py
* Issue: AttributeError: module 'pyparsing' has no attribute 'operatorPrecedence'
    * Solution: Downgraded pyparsing to version 2.4.7 using pip install pyparsing==2.4.7
* Issue: ModuleNotFoundError: No module named 'spacy'
    * Solution: Installed spaCy using pip install spacy and downloaded language model using python -m spacy download en_core_web_sm
* Issue: Missing required dataset files (snli_1.0_dev.vec not included in repo)
    * Solution: Attempted to locate/generate data, but repo does not provide preprocessing instructions or files
* Issue: FileNotFoundError: data/analysis/snli_1.0_dev.vec
    * Description: The script requires a preprocessed vector file that is not included in the repository. The repository also does not provide clear instructions or scripts to generate this file.
    * Solution: Attempted to locate or generate the dataset, but due to missing preprocessing pipeline and incomplete documentation, the file could not be created. Proceeded with analysis based on understanding of the system.

# Remaining tasks:
* Download the pretrained model
* Complete the Neurons list*

I will complete these tasks hopefully by Sunday! I apologize for the delay as this is new material to me.

Decided to restart the whole task and polish/apply debugging methods as I follow along with the documentation.

Unfortunately I could not properly complete this task.
# Steps & Issues Faced
* Cloned the repository and explored the nli folder
* requirements.txt file was missing, so installed dependencies manually
* Faced Python compatibility issue (project requires older version)
* Installed Python 3.8 using pyenv and created a virtual environment
* While installing spacy==2.2.4, encountered multiple build errors
* Downgraded setuptools, wheel, and python to resolve dependency issues
* Installation still failed due to blis dependency requiring unsupported CPU instructions on Apple Silicon
* Tried running setup in Google Colab as an alternative
* In Colab, spacy 2.2.4 failed due to incompatibility with Python 3.12
* Attempted to proceed with remaining dependencies
* While running the script, system crashed due to high memory usage when loading layer activations

# Workstation Setup
* Macbook Pro (14-inch, 2024)
* CPU: Apple M4 Pro
* GPU: Integrated Apple GPU
* Memory (RAM): 24 GB
* OS: macOS Tahoe (version 26.3)




