FlowGuard  

FlowGuard is an object detection and logging tool built using YOLOv5 and OpenCV. It processes video files or real-time camera feeds, detects objects, and logs the occurrences with timestamps. The application provides a user-friendly GUI built with Tkinter and allows users to extract a section of the log into a PDF report.  

---

## Features  
- **Object Detection:** Utilizes YOLOv5 to detect objects in video frames.  
- **Real-Time Video Capture:** Captures and processes live camera feeds.  
- **Detection Logging:** Records detected objects with timestamps in a text log.  
- **PDF Report Generation:** Extracts a section of the detection log into a PDF report.  
- **User-Friendly GUI:** Built with Tkinter for easy interaction.  

---

## Installation  
1. **Clone the Repository:**  
```bash
git clone https://github.com/yourusername/FlowGuard.git
cd FlowGuard
python -m venv venv
source venv/bin/activate  # On MacOS/Linux
venv\Scripts\activate  # On Windows

## install dependencies
pip install -r requirements.txt
Usage
Run the Application:
bash
Copy
Edit
python FlowGuard.py
Features Available in the GUI:
Upload Video: Select and analyze a video file.
Capture Real-Time Video: Start object detection using your webcam.
View Full Log: View the full detection log within the application.
Extract Log Section to PDF: Generate a PDF report for a specific time range.
Requirements
Python 3.8 or higher
OpenCV
Torch (PyTorch)
Tkinter (Built-in with Python)
FPDF (for PDF generation)
Example Screenshot

Real-Life Applications
Security and Surveillance: Detects and logs objects in security footage.
Traffic Monitoring: Tracks vehicle counts and movements for traffic analysis.
Retail Analytics: Analyzes customer movements and product interactions in retail stores.
Contributing
Contributions are welcome! Please open an issue or create a pull request for any enhancements or bug fixes.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
YOLOv5 by Ultralytics for the pre-trained object detection model.
OpenCV for video processing.
FPDF for PDF generation.
yaml
Copy
Edit

---

## **4. requirements.txt**  
```text
opencv-python
torch
numpy
fpdf
5. .gitignore
gitignore
Copy
Edit
# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]

# Logs and databases
*.log
detection_log.txt

# Virtual environment
venv/

# System files
.DS_Store
Thumbs.db

# PyCharm / VSCode settings
.idea/
.vscode/
6. LICENSE (MIT License)
markdown
Copy
Edit
MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
7. How to Upload to GitHub:
Create a New Repository: Go to GitHub and create a new repository named FlowGuard.
Initialize Local Git Repo:
bash
Copy
Edit
git init
git remote add origin https://github.com/yourusername/FlowGuard.git
Add and Commit Files:
bash
Copy
Edit
git add .
git commit -m "Initial commit for FlowGuard"
Push to GitHub:
bash
Copy
Edit
git branch -M main
git push -u origin main
8. Additional Recommendations:
Screenshots: Take screenshots of the GUI in action and save them in the screenshots/ folder.
GitHub Tags: Use tags like Object Detection, YOLOv5, OpenCV, Python, and Automation for better visibility.
GitHub Actions (Optional): Set up CI/CD for testing or deployment.
