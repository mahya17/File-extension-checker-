# File Extension Checker 📁

A simple Python program that identifies the media type of a file based on its file extension.

## About the Project

The program asks the user to enter a file name and checks its extension. Based on the extension, it prints the corresponding media type.

The comparison is **case-insensitive**, so uppercase and lowercase letters do not affect the result.

## Supported Extensions

* `.jpg` → `image/jpeg`
* `.jpeg` → `image/jpeg`
* `.gif` → `image/gif`
* `.png` → `image/png`
* `.pdf` → `application/pdf`
* `.txt` → `text/plain`
* `.zip` → `application/zip`

If the file has no extension or the extension is not supported, the program outputs:

```text
application/octet-stream
```

## How It Works

The program takes a file name as input and converts it to lowercase before checking the extension.

For example:

```text
Input: happy.jpg
Output: image/jpeg
```

```text
Input: document.PDF
Output: application/pdf
```

## What I Practiced

* `input()`
* String methods
* `lower()`
* String comparison
* `if / elif / else`
* Working with file extensions
* Case-insensitive input handling

## Technologies

* Python

## Course

This project was completed as part of **CS50's Introduction to Programming with Python** by Harvard University.
