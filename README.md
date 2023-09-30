# Splatnet3-img-stat-grab
 A project to take screenshots of Splatoon 3 Splatnet stats and convert them to CSV.
 
 Install requirements: `sudo pip3 install -r requirements.txt`

 Install tesseract (Google's OCR engine): https://tesseract-ocr.github.io/tessdoc/Installation.html
 
 Command usage: `python match.py --images {folder where images are held}`
 
 Demo images in /images, run demo with command `python match.py --images images`
 
# To do
  - [X] Player info recognition
    - [X] Assists
  - [ ] Match info recognition
    - [X] Mode
    - [ ] Map
    - [ ] Timer
    - [ ] Score
  - [ ] Conversion to CSV
 
 Lower priority:
 
  - [ ] Normalize input
  - [ ] Create GUI

# Credits
 Thanks to Leanny for providing weapon icons.
