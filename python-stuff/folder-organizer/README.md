
# Folder Organizer

A simple Python script that organizes files in a folder.

## Requirements

- Python 3

## How to Run

1. Open a terminal in the project directory.
2. Run the following command:

```bash
python3 organizer.py <folder_path>
```

Replace `<folder_path>` with the path to the folder you want to organize.

### Example

```bash
python3 organizer.py ~/Downloads
```

## Testing

Use the `make_mass.sh` script to generate test files for testing the folder organizer.

1. Give the script permission to execute:

```bash
chmod +x make_mass.sh
```

2. Run the testing script:

```bash
./make_mass.sh
```

3. Run the organizer on the generated test folder:

```bash
python3 organizer.py <test_folder_path>
```

Replace `<test_folder_path>` with the folder containing the generated test files.
