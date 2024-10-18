# Installation Guide (For devs)

## Simple setup

install node modules in frontend and backend respectively

then open backend in terminal : 

```
nodemon script.js
```

open another frontend in terminal : 

```
npm start
```

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

## Alternate (If above method does not work)

### install libraries manually

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

# Nutrition_Counter

https://docs.google.com/presentation/d/1Zfi0qlUjYUWzmfQ_Rg-6u5QeCXLvKvjQGG_46gKtbr0/edit

https://docs.google.com/document/d/1T9SCVKdqzVlnz2eeLPkzPz43b7iY5wknegbs0bIUxWQ/edit

