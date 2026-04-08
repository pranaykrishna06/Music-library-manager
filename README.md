# Music Library Manager (C Project)

## Overview

The **Music Library Manager** is a command-line based application written in **C** that allows users to manage music playlists.
Users can create playlists, add songs, delete songs, search songs, and sort songs based on different criteria.

The program uses **file handling, structures, dynamic memory allocation, and sorting algorithms** to manage and store song data.

---

## Features

* Create new playlists
* Load existing playlists
* Delete playlists
* Add songs to a playlist
* Delete songs from a playlist
* Search songs by title
* Sort songs by:

  * Rating (High to Low)
  * Artist name (A–Z)
  * Song title (A–Z)
* Save playlists to files

---

## Technologies Used

* C Programming Language
* Structures
* Dynamic Memory Allocation (`malloc`, `realloc`, `free`)
* File Handling
* Standard Libraries (`stdio.h`, `stdlib.h`, `string.h`)

---

## Project Structure

```
music-library
│
├── musiclibrary.c     # Main program
├── playlists.txt      # Stores playlist names
├── *.csv              # Playlist files
└── README.md
```

---

## How to Compile and Run

### Compile

```
gcc musiclibrary.c -o musiclibrary
```

### Run

```
./musiclibrary
```

---

## Concepts Used

* **Structures** for storing song information
* **Dynamic arrays** to store songs
* **File handling** for saving playlists
* **Searching algorithms**
* **Sorting using qsort()**

---

## Example Song Format

Songs are stored in CSV format:

```
Song Title,Artist Name,Rating
```

Example:

```
Shape of You,Ed Sheeran,5
Blinding Lights,The Weeknd,4
```

---

## Author

Pranay Krishna
