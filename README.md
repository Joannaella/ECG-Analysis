# ECG Analysis

This project provides a basic analysis of ECG signals by extracting and counting different types of cardiac event annotations. 
It is useful for studying patterns in cardiac activity and serves as a foundation for more advanced ECG data analysis projects.

## Project Overview

This code allows you to:
1. Select an ECG file in `.dat` format using a file dialog window.
2. Load and display annotations from the selected ECG file.
3. Count the occurrences of each annotation type.
4. View a summary of the counts of each annotation type in the console.

If no file is selected, a message will be displayed stating "No files were selected."

## Requirements

To run this code, you will need the following Python packages:
- `wfdb`: For reading and processing ECG files and annotations.
- `tkinter`: For the file selection dialog.
- `collections`: For counting annotation occurrences.

Install `wfdb` using pip if it's not already installed:

```bash
pip install wfdb
```

## Usage

1. **Download the MIT-BIH Arrhythmia Database** (or any other compatible `.dat` format ECG files) and have it accessible on your device.
2. Run the script, and a file dialog will prompt you to select an ECG file.
3. After selecting the file, the script will load the ECG data and count the annotation occurrences.
4. The summary of annotation types and their occurrences will be displayed in the console.

## Example

When running the script, you may see output like this:

```
Annotation Summary:
Annotation 'N': 2239 occurrences
Annotation 'A': 33 occurrences
Annotation 'V': 1 occurrence
```

This indicates the number of each type of cardiac event detected in the ECG file.

---

This project is a simple starting point for ECG analysis. It can be extended to visualize signals, perform RR interval analysis, and classify heartbeats.

## License

This project is open-source and available under the MIT License.
