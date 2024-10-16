## Overview

This is a simple, beginner-friendly, web-browser automation code that helps you find out how many Instagram posts use specific hashtags. Unlike many tools, it does not require the Instagram API, which can be difficult to connect and has usage restrictions. All you need is Python and Jupyter to get started. This tool helps content creators and social media managers optimize their hashtag strategy by identifying trending and niche hashtags.

## Features
- No Instagram API required: Avoid complicated API setups and rate limits.
- Retrieves the latest post counts for each hashtag.
- Helps balance the use of highly popular hashtags with lesser-known ones.
- Simple setup: Anyone familiar with Python and Jupyter can run it.

## Installation

To run the project locally:
1. Clone the repository:
git clone https://github.com/your-username/instagram-hashtag-usage-tracker.git

2. Install dependencies:
pip install -r requirements.txt

3. Open the project in Jupyter Notebook or any other Python environment.

## Usage

1. Prepare a text file (e.g., hashtags.txt) with the hashtags you want to analyze, one hashtag per line.

2. Run the script in Jupyter or directly from the terminal:
python hashtag_tracker.py hashtags.txt

3. The script will output the number of posts for each hashtag, giving you insights into their popularity.

## Example
Input (hashtags.txt):
#fitness
#yoga
#wellness

Output:
#fitness: 20,000,000 posts
#yoga: 10,000,000 posts
#wellness: 2,000,000 posts

## Beginner-Friendly Setup
This tool is designed for ease of use:
No advanced coding skills required: Just basic Python and Jupyter knowledge.
No Instagram API connection: Simply provide a list of hashtags and get started.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
