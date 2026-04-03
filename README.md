# 📄 AI Document Scanner (CamScanner Clone)

A Python-based **AI Document Scanner** that converts your webcam into a real-time scanner.

This system detects documents, applies **perspective transformation**, and generates a clean **scanned (black & white) output**, just like mobile apps such as CamScanner.

---

# 🚀 Features

✔ Real-time document detection
✔ Automatic edge detection
✔ Perspective correction (top-down view)
✔ Clean scanned output (black & white)
✔ Live preview of original + scanned image
✔ Smart contour detection

---

# 🛠 Technologies Used

* Python
* OpenCV
* NumPy
* Imutils
* Computer Vision (Contours + Perspective Transform)

---

# 📂 Project Structure

```id="z7m2pl"
ai-document-scanner
│
├── main.py
└── README.md
```

👉 Rename your file to **main.py** for clean structure.

---

# ⚙️ Installation

1️⃣ Install Python 3.x

2️⃣ Install required libraries:

```bash id="p9n3kr"
pip install opencv-python numpy imutils
```

---

# ▶️ How to Run

```bash id="k4p8zl"
git clone https://github.com/ravigautam7739/ai-document-scanner.git
cd ai-document-scanner
python main.py
```

---

# 🧠 How It Works

1. Webcam captures live video
2. Image is resized for processing
3. Converted to grayscale and blurred
4. Edge detection is applied
5. Contours are found and sorted
6. The largest 4-point contour is assumed as document

### 📌 Perspective Transformation

* Document corners are detected
* Image is warped into top-down view

### 📌 Scan Enhancement

* Converted to grayscale
* Adaptive threshold applied
* Produces **clear scanned document effect**

---

# 💻 Example Output

```id="m7n2wl"
[Original Camera Feed]

→ Document detected

[Scanned Output]
Clean black & white document
```

---

# 🎯 Use Cases

* Digital document scanning
* Assignment/document digitization
* Mobile scanner replacement
* Computer vision learning
* AI automation projects

---

# ⚠️ Notes

* Requires webcam
* Works best with clear document edges
* Good lighting improves accuracy
* Background should contrast with document

---

# 🔮 Future Improvements

* Save scanned images as PDF
* Auto-capture when document is stable
* Multi-page scanning
* Mobile integration
* GUI interface

---

# ⭐ Support

If you found this project useful, give it a **star ⭐**.

---

# 📱 Follow for More Projects

I regularly share **Python, AI, and real-world automation projects**.

Stay tuned 🚀
