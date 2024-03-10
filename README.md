# Web Scraping and File Download Script

## Description
This Python script automates the process of logging into the "LieberLeichter" website, navigating through specified links, and downloading PDF and MP3 files from the associated pages. It is designed to simplify the retrieval of educational materials from the website.

## Video Preview

[![Video Preview](https://github.com/DevRex-0201/Project-Images/blob/main/video%20preview/Py-Scraping-PDF-MP3-Downloader.png)](https://drive.google.com/file/d/1eJHEY_-FR-wwVOaV-_YZGTKIwPx72ayI/view?usp=drive_link)

## Features
- **Automated Login:** The script uses a provided username and password to log in to the "LieberLeichter" website.
- **Link Processing:** Specified links are traversed, and the associated pages are scraped for PDF and MP3 file links.
- **Download Functionality:** PDF and MP3 files are automatically downloaded to a local folder.
- **Error Handling:** The script includes error handling to manage potential HTTP errors during login and link processing.

## Requirements
- Python 3.x
- Required Python packages: `requests`, `BeautifulSoup`

## How to Use
1. Install the required Python packages using `pip install requests beautifulsoup4`.
2. Replace the `loginname` and `password` variables with your actual login credentials.
3. Adjust the `links` list with the specific URLs you want to process.
4. Run the script.

## Usage Example
```bash
python lieberleichter_downloader.py
```

## Output
Downloaded files will be saved in the `downloads` folder in the project directory.

## Disclaimer
This script is intended for personal use only. Use it responsibly and in accordance with the terms of service of the "LieberLeichter" website.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- This script was created for educational purposes and to streamline the process of accessing materials from the "LieberLeichter" website.
- Special thanks to the developers of the `requests` and `BeautifulSoup` libraries for their valuable contributions to the Python community.
## Disclaimer

This script is provided for educational purposes and may need customization to work with specific websites. Use it responsibly and respect the website's terms of service. The author is not responsible for any misuse or legal consequences resulting from the use of this script.
