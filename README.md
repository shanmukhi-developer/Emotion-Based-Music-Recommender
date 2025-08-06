<h1 align="center">🎧 Emotion Based Music Recommender</h1>

<p align="center">
  A real-time web app that detects your facial emotion via webcam and recommends songs that match your mood.<br>
  Built using <strong>Streamlit</strong>, <strong>MediaPipe</strong>, and <strong>Keras</strong>.
</p>

<hr>

<h2>🚀 Key Features</h2>
<ul>
  <li>Real-time emotion detection through webcam</li>
  <li>Facial landmark recognition using MediaPipe Holistic</li>
  <li>Deep learning-based emotion classification</li>
  <li>Song recommendations via YouTube or Spotify</li>
  <li>Streamlit web interface for fast deployment</li>
</ul>

<h2>🛠 Tech Stack</h2>
<table>
  <tr><td><strong>Frontend</strong></td><td>Streamlit</td></tr>
  <tr><td><strong>Webcam Streaming</strong></td><td>streamlit-webrtc</td></tr>
  <tr><td><strong>Model</strong></td><td>TensorFlow/Keras</td></tr>
  <tr><td><strong>Face & Hand Detection</strong></td><td>MediaPipe</td></tr>
  <tr><td><strong>Video Processing</strong></td><td>OpenCV</td></tr>
</table>

<h2>📂 Project Structure</h2>

<pre>
emotion-music-recommender/
├── model.h5              # Trained deep learning model
├── labels.npy            # Labels used in prediction
├── emotion.jpg           # Project thumbnail
├── emotion.npy           # Stores latest predicted emotion
├── music.py              # Main web app script
├── requirements.txt      # Python package list
└── README.md             # Project documentation
</pre>

<h2>📦 Installation</h2>

<ol>
  <li>Clone the repository:<br>
    <code>git clone https://github.com/shanmukhi-developer/Emotion-Based-Music-Recommender.git</code>
  </li>
  <li>Navigate into the directory:<br>
    <code>cd emotion-based-music-recommender</code>
  </li>
  <li>Install dependencies:<br>
    <code>pip install -r tempCodeRunnerFile.py</code>
  </li>
  <li>Run the app:<br>
    <code>streamlit run music.py</code>
  </li>
</ol>

<h2>🧪 How to Use</h2>
<ol>
  <li>Enter language, singer, and genre in the provided fields</li>
  <li>Allow webcam access to detect your emotion</li>
  <li>Click the <strong>"Recommend me"</strong> button</li>
  <li>You're redirected to matching songs on YouTube or Spotify!</li>
</ol>

<h2>🎭 Emotions Detected</h2>
<ul>
  <li>Happy 😊</li>
  <li>Sad 😢</li>
  <li>Angry 😠</li>
  <li>Neutral 😐</li>
</ul>

<h2>🎯 Model Details</h2>
<p>
  - The model uses face and hand landmarks extracted via MediaPipe<br>
  - Preprocessed coordinates are input to a trained neural network (Keras)<br>
  - The output label is saved to a temporary file and used for recommendations
</p>

<h2>🧠 Future Improvements</h2>
<ul>
  <li>Train with more diverse datasets to improve accuracy</li>
  <li>Add voice-based interaction for selection</li>
  <li>Support offline music playback</li>
  <li>Deploy as a mobile app</li>
</ul>

<h2>👨‍💻 Author</h2>
<p>
  <strong>Nadipudi Shanmukhi Satya</strong><br>
  AI/ML Enthusiast | Developer<br>
  📬 shanmukhinadipudi@gmail.com | 💻 <a href="https://github.com/shanmukhi-developer">GitHub</a>
</p>

<h2>📸 Preview</h2>
<img src="emotion.jpg" width="600"/>
<hr>

<p align="center">
  ⭐️ If you found this project useful, feel free to star it and share it with others!
</p>
