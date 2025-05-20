# Face Recognition System

This is a Python-based face recognition tool using the `face_recognition` and `OpenCV` libraries. It detects and identifies known faces from a local image using pre-encoded faces stored in a `faces/` directory.

---

## 🧠 Features

- Detects all faces in a given image
- Matches against known faces (pre-encoded)
- Draws bounding boxes and labels over detected faces
- Displays the image in a real-time OpenCV window
- Exits when you press `q`

---

## 📁 Project Structure

```
face-recognition/
│
├── faces/               # Folder of known face images (.jpg or .png)
│   ├── yousef.jpg       # Example: encodes as "yousef"
│
├── test.jpg             # Image to scan for known faces
├── your_script.py       # Your main recognition script
```

---

## 📦 Requirements

- Python 3.7+
- `face_recognition`
- `opencv-python`
- `numpy`
- `art` (for startup banner)

Install dependencies:

```bash
pip install face_recognition opencv-python numpy art
```

---

## 🚀 Usage

1. Add known face images to the `faces/` folder (e.g., `john.png`)
2. Place your test image in the root directory (e.g., `test.jpg`)
3. Run the script:

```bash
python your_script.py
```

Press `q` to close the OpenCV window after face detection.

---

## 🖼️ Output

- Draws blue rectangles around detected faces
- Labels recognized faces with their names
- Unknown faces are labeled `"Unknown"`

---

## 🛡 Ethical Notice

This project is for educational and personal use only. Always obtain consent before capturing or analyzing someone’s facial data.

---

## 📄 License

This project is open-source under the MIT License.
