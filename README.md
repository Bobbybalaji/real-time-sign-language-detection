Sign Language to Text Translator ✋🔤
This project is a real-time Sign Language Detection system using computer vision and deep learning. It detects individual letters, numbers, and predefined words/phrases from live webcam feed and converts them into readable text.

Features
📸 Real-time hand tracking using MediaPipe

🔠 Letter & number detection using a trained ML model

🧠 Word/phrase detection using a trained deep learning model

💬 Builds words/sentences using space and enter keys

🎥 Webcam interface with guiding box and landmark visualization



How It Works
Run the program.


You'll see:

Choose Detection Mode:
1. Letter Detection
2. Word Detection
3. Exit
Enter your choice (1, 2, or 3):
Choose:

1 for letter & number detection

2 for word/phrase detection

3 to exit




Letter Detection Mode
A green box appears on the webcam feed.
Show your hand gesture inside the box.



Press:

Space ➡️ to add the detected letter/number to a word

Enter ➡️ to move the word to the sentence

Q ➡️ to quit

Word Detection Mode
Detects predefined actions/phrases like:

hello, thanks, iloveyou, no, yes, all the best

Folder Structure

.
├── MP_Data/                # Preprocessed hand landmark data
├── app1.py                 # Main application script
├── best_model1.keras       # Trained deep learning model for word detection
├── model.p                 # Pickled ML model for letter/number detection
├── requirements.txt        # List of Python dependencies
├── sign-to-text(1).ipynb   # Notebook for letter detection
├── trainin.ipynb           # Notebook for model training


Dependencies
Install required packages with:

pip install -r requirements.txt
Models Used
MediaPipe Holistic & Hands for landmark detection

ML Classifier (model.p) for letters & numbers

Deep Learning (Keras) model (best_model1.keras) for phrase detection


Credits
Dataset: From Kaggle 

Developed by: Pandilla balaji and PannemMohan

