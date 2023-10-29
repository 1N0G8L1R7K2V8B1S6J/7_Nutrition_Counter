# Installation Guide (For devs) :


## Simple setup :

* install pipreqs and use it to generate requirements.txt:
```
    pip install pipreqs
    pipreqs ./
```

* install all libraries mentioned in requirements.txt:
```
    pip install -r requirements.txt
```

* replace the url in *camio.py* to your ip webcam to use mobile cam

***

## Alternate (If above method does not work) :

### install libraries manually:

* upgrade pillow (for simpler image I/O) :

```
    python3 -m pip install --upgrade pip
    python3 -m pip install --upgrage pillow
```
* xlib
```
    pip install python-xlib
```

* install opencv :

```
    pip install opencv-python
```

* tesseract :

```
    sudo apt-get install tesseract-ocr
    pip intall pytesseract
```

***