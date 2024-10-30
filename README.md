# TTS-Speecht5
Fine-tuning Speecht5 for English with a focus on technical vocabulary and for Tamil language

### Overview of Text-to-Speech (TTS)

Text-to-Speech (TTS) technology converts written text into spoken voice output. It utilizes various algorithms and models to produce human-like speech, often incorporating natural language processing (NLP) and machine learning techniques.

### Applications of TTS

1. **Accessibility**: Enhances accessibility for visually impaired individuals by reading text aloud in applications like screen readers.
2. **Virtual Assistants**: Powers voice assistants (e.g., Siri, Alexa) to interact with users through spoken language.
3. **E-Learning**: Facilitates learning by converting written content into audio, making it easier for auditory learners.
4. **Navigation Systems**: Provides voice guidance in GPS devices and mobile applications.
5. **Entertainment**: Used in audiobooks, video games, and animations to create character voices.
6. **Customer Service**: Automates responses in call centers, enhancing user interaction with voice bots.

### Importance of Fine-Tuning

Fine-tuning TTS models is crucial for several reasons:

1. **Customization**: Tailors the model to specific voices, accents, or styles, making the output more relatable to target audiences.
2. **Improved Quality**: Enhances the naturalness and intelligibility of the generated speech, resulting in a better user experience.
3. **Domain-Specific Performance**: Adapts the model to particular vocabularies or terminologies relevant to specific industries (e.g., medical, legal), improving accuracy.
4. **Efficiency**: Reduces the amount of training data and time required to achieve satisfactory performance compared to training from scratch.
5. **Personalization**: Allows for individual user preferences, such as speech speed, tone, and emotional expression, enhancing user engagement.

### Setup and Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Tejas1206/TTS-Speecht5
   cd TTS-Speecht5
   ```
2. **Set up a Virtual Environment**
   ```Shell
    python3 -m venv venv
    venv\Scripts\activate  
    ```
3. **Install the required dependencies**
   ```Shell
    pip install -r requirements.txt  
    ```
4. **Run Jupyter Notebook**
   ```Shell
    jupyter notebook  
    ```
5. **Run the TTS-English.ipynb and speecht5-tts-ta.ipynb by setting the huggingface token and the location of the fine-tuned model**

### Web Application

**huggingface link (TTS-English)**: https://huggingface.co/spaces/tejas1206/TTS-SpeechT5

**huggingface link (TTS-Tamil)**: https://huggingface.co/spaces/tejas1206/TTS-SpeechT5-tamil
