# Welcome to `CodeTracker 1.0`
### A Python utility for counting lines of code in your Python projects and generating insights.

- **Mission:** CodeTracker's goal is to provide a straightforward and efficient way to quantify your coding efforts. Whether you're tracking progress in a learning journey or monitoring the growth of a project, CodeTracker is your go-to tool for quick and accurate line count analytics and visualizations.
- **Languages:** Python

## Features

- **Line Counting**: Accurately count lines of code in `.py` files within any selected directory.
- **Folder Flexibility**: Process multiple folders sequentially, aggregating line counts across your projects.
- **Interactive Console Interface**: Simple prompts guide you through selecting folders and reviewing total line counts.
- **Continuous Tracking**: Option to add more folders for line count without restarting the program.
- **User-friendly**: Designed for ease of use, regardless of your experience level with coding or tools.

---
## Directory Structure

```
codetracker/
│
├── helpers/
│   ├── utilities.py  # functions for processing files and folders
│   │   ├── count_lines_in_file()
│   │   └── process_folder()
│   │
│   ├── stats.py  # functions for visualizing and summary statistics
│   │   ├── ...
│   │   └── ...
│   │
│   └── gui.py  # simple GUI for folder selection
│       └── select_folder()
│
├── tests/
│   ├── test_input/  # sample Python files for testing
│   │   ├── test_script1.py
│   │   └── ...
│   │
│   └── test_output/  # output of CodeTracker on test files
│       └── ...
│
├── README.md          # Documentation and usage guide
├── codetracker.py     # Main script to run CodeTracker
└── requirements.txt   # Required Python libraries

```

---
## Installation and Usage

### Prerequisites
- Python 3.x

### Setup
1. Clone the repository:
   ``` bash
   git clone https://github.com/YourUsername/codetracker.git
   ```
2. Navigate to the CodeTracker directory:
   ```bash
   cd codetracker
   ```
### Running CodeTracker
Execute the script and follow the on-screen instructions:
```bash
python codetracker.py
```

#### CodeTracker Prompt Sequence
1. **Folder Selection:** Opens a browse window so the user can choose the folder containing `.py` files.
2. **Line Count Display:** Displays the line count for the selected folder and the cumulative total.
3. **Additional Folder:** Asks if the user wants to add another folder for line counting.

---
## Contributing
Contributions to CodeTracker are welcome. Feel free to fork the repository, make changes, and submit pull requests.
