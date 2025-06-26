# Pc-checker
A C++ scanner that searches your system for known Roblox cheat traces like Mooze, Matrix, Xeno, and more. Shows scan progress and logs all detections to a file.

# 🕵️ Roblox Cheat Scanner

A lightweight C++ tool that scans your Windows system for known **Roblox cheat traces** by searching for suspicious file and folder names.

---

## 🔍 Features

- ✅ Scans the entire `C:\` drive (or custom path)
- ✅ Detects known cheat-related files/folders:
  - `mooze`, `matrix`, `xeno`, `swift`
  - `cheat`, `loader`, `newuimatrix`
- ✅ Real-time **progress display** during scan
- ✅ All findings logged to `CheatScanResults.txt`
- ✅ Simple access control via key prompt

---

## 🔐 Access Key

To run the scanner, you'll need to enter a key when prompted.  
The current key is: 656432


---

## 🛠️ How to Use

1. **Download the executable** or compile the code manually (see below).
2. **Run as Administrator** for full file access.
3. Enter the access key.
4. Let the scanner run — progress will be shown live.
5. Results are saved to `CheatScanResults.txt` in the current directory.

--

## 📁 Output Example

[MATCH] C:\Users\Example\AppData\Roaming\loader.zip
[MATCH] C:\Program Files\swift.exe
[...]
=== Scan Summary ===
Total suspicious items found: 5


