# Youtube-Slide-Slicer



**YouTube SlideSlicer** is a desktop application built using **Python** and **Tkinter** that empowers users to extract slide-like frames from YouTube videos. It features customizable key frame detection based on frame interval and similarity threshold, compiling the extracted frames into a downloadable PDF.


---

## 🚀 Features

- **Extract Slides from YouTube**: Provide a video URL and extract visually distinct frames.
- **Customizable Settings**: Choose frame interval (in seconds) and frame similarity threshold.
- **PDF Generation**: Automatically compile extracted slides into a clean PDF.
- **Real-Time Progress Bar**: Stay updated with a progress bar while the video is being processed.

---

## 📁 Project Structure

```
RiyazAbdul-Youtube-Slide-Slicer/
├── ReadMe.md
├── LICENSE
├── main.py                # GUI and application entry point
├── requirements.txt       # Python dependencies
└── slide_extractor.py     # Core slide extraction logic
```

---

## 🧩 Requirements

Ensure Python 3.7+ is installed. Then, install the necessary dependencies with:

```bash
pip install -r requirements.txt
```

**Dependencies include:**

- `tkinter` – GUI library (usually comes with Python)
- `pillow` – Image handling
- `reportlab` – PDF generation
- `opencv-python` – Frame processing
- `numpy` – Image comparison
- `pytube` – YouTube video downloading

Make sure `tkinter` is installed (it is included with most Python distributions, but on Linux you may need to install it separately using your package manager).

---

## ⚙️ Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/RiyazAbdul/Youtube-Slide-Slicer.git
   cd crackerYoutube slide slicer
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:

   ```bash
   python main.py
   ```

---

## 🧪 How to Use

1. **Launch the App**: Run `main.py` to open the graphical interface.
2. **Paste YouTube URL**: Enter the URL of the video you want to extract slides from.
3. **Set Frame Interval**: Choose how frequently (in seconds) to extract frames.
4. **Adjust Similarity Threshold**: Define how similar consecutive frames need to be (0.0 to 1.0).
5. **Click "Extract Slides"**: The application will download the video and extract the slides.
6. **Click "Generate PDF"**: Once extraction is complete, generate a PDF from the slides and save it.

---

## 📂 Output

- Extracted slides are saved in a local `slides/` folder.
- PDF output is saved to a location of your choice.

---

