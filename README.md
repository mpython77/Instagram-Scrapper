# Instagram Reels Scraper (Demo Version)

A Python-based automation tool that demonstrates the capabilities of scraping Instagram reels using Selenium WebDriver. This demo version is designed to showcase the functionality by downloading 2 reels from any public Instagram profile.

## 🚀 Features

- Runs in headless mode (background)
- Extracts data from latest 2 reels
- Saves metadata to Excel file
- Downloads reel videos
- Handles various error cases
- User-friendly console interface

## 📋 Requirements

- Python 3.7+
- Chrome Browser
- ChromeDriver

## 📦 Dependencies

```bash
selenium==4.15.2
pandas==2.1.3
requests==2.31.0
```

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/instagram-reels-scraper.git
cd instagram-reels-scraper
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Make sure you have Chrome and ChromeDriver installed

## 💻 Usage

1. Run the script:
```bash
python demo_scraper.py
```

2. Enter an Instagram username when prompted

3. The script will:
   - Check if the user exists
   - Verify if they have reels
   - Download data from 2 reels
   - Save metadata to 'demo_reels_data.xlsx'
   - Save videos to 'demo_reels' folder

## 📝 Output

The script generates two types of output:

1. Excel file (demo_reels_data.xlsx) containing:
   - Reel Number
   - Caption
   - Likes count
   - Comments count
   - Posted time
   - Download URL

2. Video files in 'demo_reels' folder:
   - demo_reel_1.mp4
   - demo_reel_2.mp4

## ⚠️ Error Handling

The script handles various scenarios:
- Non-existent users
- Private profiles
- Profiles without reels
- Network issues
- Download failures

## 🔒 Limitations

This demo version:
- Only downloads 2 reels
- Works with public profiles only
- Requires stable internet connection
- Is for demonstration purposes only

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚖️ Legal Disclaimer

This tool is for demonstration purposes only. Users are responsible for complying with Instagram's terms of service and applicable laws when using this tool.

## 🤝 Contributing

This is a demo version. For the full version or to contribute, please contact the repository owner.

## 📫 Contact

Doston - [kelajak054@email.com]
Project Link: [https://github.com/mpython77/Instagram-Scrapper]
