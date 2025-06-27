# 🏥 Hospital Management System

A simple C++ console application that manages hospital records — patients, doctors, and appointments — designed to showcase object-oriented programming and data handling in C++.

---

## 🚀 Features

- 👤 Add, update, and delete **patients** and **doctors**
- 📅 Schedule and cancel **appointments**
- 📋 View detailed lists for patients, doctors, and appointments
- 💾 Persist data to text files for storage and retrieval

---

## 🧠 Tech Stack

- Language: **C++**
- Features: Classes, file I/O (text-based persistence)
- Build System: Standard `g++` or any modern C++ compiler

---

## 📁 Project Structure

Hospital-Management-System/
├── src/
│ ├── main.cpp # Application entry
│ ├── Patient.cpp/.h
│ ├── Doctor.cpp/.h
│ ├── Appointment.cpp/.h
│ └── HospitalManager.cpp/.h
├── data/ # Storage files (e.g. patients.txt)
├── Makefile or CMakeLists.txt (optional)
└── README.md


---

## ⚙️ How to Build & Run

### Using g++:
```bash
g++ src/*.cpp -o hms
./hms
```
### Using Cmake:
```bash 
mkdir build && cd build
cmake ..
make
./hms
```

### 🛠️ Usage
Run the compiled executable (./hms).

Use the console menu to:

Register patients/doctors

Schedule or cancel appointments

View or edit records

Data is saved automatically to files under data/.

### 📌 Notes
Designed as a learning project—no GUI or database integration.

Easily extendable with file format upgrades (e.g. CSV, JSON) or SQL backends.

### ⭐ Contributing
Contributions are welcome! Open an issue or pull request to improve the system—adding search, user authentication, or report generation would be great enhancements.

### 📝 License
This project is provided for educational purposes only.
Feel free to modify and distribute under the MIT License.

---

Let me know if you'd like to include build badges, screenshots, or instructions for Windows vs. Unix!
