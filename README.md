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
git clone https://github.com/andrewjohnaj/python-instagram-hashtag-usage.git
2. Install dependencies:
pip install -r requirements.txt
3. Open the project in Jupyter Notebook or any other relevant IPython notebook environment.

## Usage

1. Prepare a text file (e.g., hashtags.txt) with the hashtags you want to analyze, one hashtag per line. Place it in the root folder.
2. Run the first 2 code cells in the notebook that import the libraries and set up the automation browser and website. 
3. Switch to the browser and log in to your Instagram account using the credentials. Click on the Search icon to open the panel and search box.<br/>
![image](https://github.com/user-attachments/assets/78dd90b7-946d-4481-9103-b926b3b9c0cd)
4. The page is now ready to receive the rest of the automation loop from the third code cell. Once the hashtags from the text file are looped through, the script will output the number of posts for each hashtag in an Excel file, giving you insights into their popularity.

## Example
Input (hashtags.txt):<br/>
![image](https://github.com/user-attachments/assets/7c98babf-7172-4dcf-a0b1-eff75024ddff)

Output:<br/>
![image](https://github.com/user-attachments/assets/846c07fe-f608-49f7-ab12-a9746554f29b)

## Beginner-Friendly Setup

This tool is designed for ease of use:
- No advanced coding skills are required: Just basic Python and Jupyter knowledge.
- No Instagram API connection: Simply provide a list of hashtags and get started.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
