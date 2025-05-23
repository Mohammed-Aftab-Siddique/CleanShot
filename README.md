# 🧹 Duplicate Image Remover with GUI, Progress Bar & Logging

This is a Python-based tool that allows users to remove duplicate images from a selected folder. The tool uses hashing to identify duplicate images, shows a real-time progress bar, and logs all deleted files into a `deleted_images_log.txt` file for future reference.

---

## 🚀 Features

- ✅ Select a folder using the GUI
- ✅ Detect and delete duplicate images using image content hashing
- ✅ Real-time progress bar for processing status
- ✅ Automatically logs deleted file paths with timestamps
- ✅ Safe, lightweight, and open source

---

## 🖼 Supported Image Formats

- `.jpg`
- `.jpeg`
- `.png`
- `.bmp`
- `.gif`

---

## 🛠 Installation

Make sure Python is installed. Then install the required library:

```bash
pip install pillow

````
## ▶️ How to Use
1. Run the script:
     python duplicate_image_remover.py
2. A GUI will pop up to let you select the folder containing images.
3. The tool will begin scanning, display a progress bar, and delete any duplicates it finds.
4. Once done, a message box will show the result, and a log file deleted_images_log.txt will be created in the selected folder.

## 📝 Log File
Each run appends to deleted_images_log.txt in the selected folder, containing:
- Timestamp of the run
- List of deleted image paths

## 👨‍💻 Author
Developed by: 
- Abhishek Satpathy [www.abhisat.com]
- Mohammed Aftab Siddique [www.thecodingfeast.co.in]

For feedback or contributions, feel free to open an issue or submit a pull request.
