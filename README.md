
# Named Entity Recognition (NER) with Hugging Face Transformers

This project demonstrates how to perform Named Entity Recognition (NER) using the Hugging Face Transformers library. It extracts named entities from text, categorizes them (such as persons, organizations, locations, and dates), and formats the results for potential integration into knowledge graphs or other applications.

## Features
- **NER Extraction**: Uses a pre-trained BERT model to identify and classify named entities in a given text.
- **Entity Formatting**: Formats the extracted entities for easier processing and integration.
- **Filtering Capabilities**: Filters extracted entities by type (e.g., Person, Organization, Location).
- **Simple and Modular Structure**: The code is organized in a class for easy reuse and extension.

## Prerequisites

1. **Python**: Ensure you have Python 3.7 or higher installed on your machine.
2. **Install Required Libraries**:
   - Install the necessary packages by running:
     ```bash
     pip install transformers pandas
     ```

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/ner-huggingface.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd ner-huggingface
   ```

3. **Install Dependencies**:
   Make sure to install the required Python libraries as mentioned above.

## Usage

1. **Run the Script**:
   To execute the NER extraction, run the following command:
   ```bash
   python ner_extractor.py
   ```

   Replace `ner_extractor.py` with the filename if you name it differently.

2. **Modify the Sample Text**:
   You can change the sample text within the `main()` function in the code to test with different inputs.

3. **View Results**:
   The script will output the extracted entities, including their types and confidence scores. It also provides filtered results for specific entity types like Persons and Organizations.


## Customization

Feel free to customize the model used for NER by changing the model name in the `NERExtractor` class constructor. You can explore different models available on the Hugging Face Model Hub: [Hugging Face Model Hub](https://huggingface.co/models).
