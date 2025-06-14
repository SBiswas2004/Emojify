![Screenshot 2025-06-02 095840](https://github.com/user-attachments/assets/19529803-819f-4d6e-9a76-d3d65a8a9b2e)

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
</head>
<body>

  <h1>Emojify</h1>

  <h2>Project Description</h2>
  <p>
    Emojify is a machine learning-based application that identifies facial expressions from live webcam images and maps them to corresponding emojis in real time.
    It uses deep learning (CNN) and OpenCV to classify emotions such as happiness, sadness, and anger, and displays the matching emoji on screen.
  </p>

  <h2>How to Run the Project</h2>
  <ol>
    <li>Make sure you have Python 3.8+ installed on your system.</li>
    <li>Install the required libraries by running:
      <pre>pip install opencv-python pillow numpy keras tensorflow</pre>
    </li>
    <li>Place your trained model weights as <code>model.weights.h5</code> and your emoji images in an <code>emojis</code> folder.</li>
    <li>Run the application with:
      <pre>python gui.ipynb</pre>
    </li>
    <li>Interact with the GUI to see live emotion-to-emoji conversion from your webcam feed.</li>
  </ol>

</body>
</html>
