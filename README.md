# Zip Archive Tools

This repository contains a set of PHP tools for working with ZIP archives. The project includes functionalities to transfer data from a MySQL database to a text file, compress the file into a ZIP archive, extract ZIP files, and allow users to upload and extract multiple ZIP files.

## Features

1. **Data Transfer and ZIP**: Retrieves data from a MySQL database and writes it to a text file, which is then added to a ZIP archive.
2. **ZIP Archive Creation and Content Addition**: Creates a ZIP file, adds content to it, and even creates folder structures within the archive.
3. **Extracting ZIP Files**: Extracts the contents of a ZIP archive to a specified directory.
4. **Bulk File Upload**: Allows users to upload ZIP files and extract their contents.

## Usage

### Transfer Data from Database and Create ZIP Archive

- Fetches article titles and content from a database and writes them into a `data.txt` file.
- This file is then compressed into a `data.zip` archive.

### Extract ZIP File

- Extracts the contents of a ZIP archive into a designated folder.

### Bulk File Upload

- Users can upload ZIP files, and the contents will be extracted and saved in the system.

## Requirements

- PHP 7.0 or higher
- MySQL database
- Bootstrap 5 for UI

## Installation

1. Clone or download the project.
2. Set up a MySQL database and import the necessary tables for the `education` database.
3. Configure database connection settings in the PHP files.
4. Run the project on a PHP server.

## Contribution

This project is open-source. Feel free to fork the repository and submit pull requests.

## License

MIT License
