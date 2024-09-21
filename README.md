# desktop_cleaner

A simple Python script that organizes files on your desktop (or specified folder) by moving them into subfolders based on their file extensions. This helps keep your workspace tidy and makes it easier to find files.

## Installation

You can run this script in Visual Studio Code or any terminal that supports Python. Ensure you have Python installed on your machine.

1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/DesktopCleaner.git
   ```

2. Navigate to the project directory:
   ```bash
   cd DesktopCleaner
   ```

3. Install any necessary dependencies (if applicable).

## Usage

To use the Desktop Cleaner, simply run the script. By default, it will clean the `Downloads` folder. You can modify the `folder_path` variable in the script to point to the folder you want to clean.

Run the script using:
```bash
python desktop_cleaner.py
```

### Example Output

When you run the script, it will output messages indicating which files were moved or skipped:

```
Desktop Cleanup Script
Moved: example.txt -> TXT Files/
Skipped: image.png already exists in PNG Files/
Cleaning complete
```

## Features

- Organizes files into subfolders based on their extensions (e.g., `TXT Files`, `JPEG Files`).
- Avoids overwriting existing files in the destination folders.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m "Add some feature"`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.
