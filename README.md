# Named-Entity-Recognition-Using-LSTM
A project using a bidirectional LSTM model in Keras/TensorFlow to classify named entities like persons, organizations, and locations in text data. Includes data preprocessing, model training, and evaluation with accuracy and loss visualizations for performance tracking.

## What the Project Does
This project implements Named Entity Recognition (NER) on text data using a bidirectional LSTM model. The primary goal is to recognize and classify named entities in text, such as persons, organizations, locations, etc. The model is trained to identify these entities in sentences and tag them according to the IOB-2 scheme.
##Why the Project is Useful
NER is a fundamental task in Natural Language Processing (NLP) with applications in information extraction, machine translation, question answering, and text summarization. By leveraging deep learning techniques, this project demonstrates how models like LSTM can effectively recognize entities in text data, making it an invaluable tool for processing and understanding large-scale text data.

## Technologies Used
- **Python**: The programming language used for implementation.
- **Keras & TensorFlow**: Deep learning frameworks for building and training the LSTM model.
- **Pandas**: Data manipulation and analysis library for handling datasets.
- **NumPy**: Library for numerical computations.
- **Matplotlib/Seaborn**: Libraries for data visualization.

## Key Features
- **Bidirectional LSTM Model**: Utilizes a bidirectional LSTM to capture the context of words in both directions, improving the accuracy of entity recognition.
- **IOB-2 Tagging Scheme**: Handles entity tagging using the IOB-2 format for fine-grained entity recognition.
- **Customizable**: Easy to adapt and expand for recognizing new types of entities.
- **Accuracy**: Achieves high accuracy in named entity recognition on the dataset.
- **Visualization**: Includes loss and accuracy graphs to monitor model performance during training.

## Getting Started
1. **Clone the Repository**:
   git clone https://github.com/your_username/Named-Entity-Recognition-LSTM.git
   cd Named-Entity-Recognition-LSTM
   
2. **Install Required Libraries**:
   Make sure you have Python installed, then install the necessary packages:
   pip install -r requirements.txt
   
3. **Run the Jupyter Notebook**:
   Open the Jupyter notebook file (named_entity_recognition.ipynb) in your preferred environment (Jupyter Notebook or Google Colab), and follow the instructions provided to 
   execute the NER analysis.
   
4. **Results**:
   After running the notebook, you will see the model's accuracy and loss plots. You can evaluate the model on the test data to see how well it recognizes named entities.

## Results
The model achieves high accuracy in recognizing entities such as persons, organizations, locations, and geopolitical entities.
Example entities recognized:
- PER (Person)
- ORG (Organization)
- GPE (Geopolitical Entity)
- TIM (Time indicator)
- EVE (Event), etc.

## Getting Help
For any questions or issues regarding the project, please open an issue on the repository, and I will be happy to assist. You can also check the TensorFlow and Keras documentation for more information on using deep learning models.

## Maintainers and Contributors
This project is maintained by **Esha Govardhan, Pragati Gadkar, Tisha Nawani, Amrapali Chandanshiv**. Contributions are welcome! If you would like to contribute, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
