# Xslxconverter

This is a simple application that solves one problem. You give it an xlsx document and the application will convert it to csv.

# Why did you build Xslxconverter?

I use a Mac. I don't have Microsoft Office installed on my laptop. I shouldn't have to download MS Office, LibreOffice, or a full suite to convert a file.

# What are the benefits of using Xslxconverter?

It's small, focused on one thing.  That's converting an xlsx file to csv.

It's also secure. There are online service that offer a similar service. You don't know what they're doing with your data.

# What did you use to build Xslxconverter?

1. [Python 3](https://www.python.org/download/releases/3.0/) - Standard library functions were used
2. [Kivy](https://github.com/kivy/kivy) - Open source UI framework written in Python, running on Windows, Linux, macOS, Android and iOS
3. [xlsx2csv](https://github.com/dilshod/xlsx2csv) - Convert xslx to csv, it is fast, and works for huge xlsx files

# How do you run the application?

From the command line:

```pip3 install -r requirements.txt```

```python3 main.py```
