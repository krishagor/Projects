# Face Recognition Project

This project is a face recognition system built using Python, OpenCV, and the `face_recognition` library. It is capable of detecting and recognizing faces in real-time using webcam input, and also comparing two images to determine whether they contain the same person.

---

# 🚀 Features

- ✅ Real-time face detection and recognition using webcam
- ✅ Image-to-image face comparison
- ✅ Easy to set up and run
- ✅ Organized codebase with modular structure
- ✅ Demo images of public figures used for testing

---

# 🧠 Technologies Used

- Python 3.x
- OpenCV (`opencv-python`)
- dlib (dependency of `face_recognition`)
- `face_recognition` Python library

---

# 📁 Project Structure

SOURCE CODE/
├── images/              # Contains images of known public figures (for demo/testing)
├── .gitignore           # Ignored files/folders
├── image_comparison.py  # Script to compare two images
├── main_video.py        # Main script for webcam-based face recognition
├── README.md            # Project documentation
├── simple_facerec.py    # Encapsulated face recognition logic

---

⚙️ Installation

Make sure you have Python 3.x installed. Then install the dependencies:

```bash
pip install opencv-python face_recognition
Note: face_recognition also requires dlib, which may need CMake and build tools on your system. On macOS:

brew install cmake
pip install dlib
Or just use:

pip install cmake
pip install dlib
🧪 Usage

➤ Real-time Face Recognition
python main_video.py
This will start your webcam, detect faces, and match them with known ones.
➤ Image Comparison
python image_comparison.py
This will compare two images and print whether the faces match.
📝 Notes

All images used in the public_figures folder are for educational and demonstration purposes only.
You can add your own images in the folder to test with different faces.
Make sure all test images are clear and front-facing for best results.

📌 Future Improvements
Add GUI interface using Tkinter or PyQt
Train on larger datasets
Integrate with databases for user profiles
Add face recognition accuracy metrics

👩‍💻 Author
Krisha Gor
BSc in Information Technology (IT)
GitHub: https://github.com/krishagor