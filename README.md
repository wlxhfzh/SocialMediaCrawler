# SocialMediaCrawler

## Overview

SocialMediaCrawler is a specialized tool designed for academic and research purposes, enabling users to systematically collect and organize textual and multimedia content from various social media platforms, including Weibo and other major self-media sites. The crawler extracts posts based on user-defined keywords, processes the acquired data, and structures it into analyzable formats for subsequent research.

## Features

- **Keyword-based Crawling**: Automatically collects text posts containing specified keywords across supported social media platforms.
- **Multimedia Content Handling**: Downloads and categorizes associated images and videos, saving them into organized directories.
- **Structured Data Output**: Consolidates collected textual data into CSV files, facilitating efficient data analysis and processing.
- **Extensible Architecture**: Designed for easy adaptation to new platforms and media types.

## Use Cases

- Sentiment analysis of social media discourse
- Media studies and communication research
- Trend detection and topic modeling
- Dataset preparation for machine learning projects

## Requirements

- Python 3.7+
- Dependencies listed in `requirements.txt`

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/wlxhfzh/SocialMediaCrawler.git
   cd SocialMediaCrawler
   ```

2. Install necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure your keywords and platform settings in `config.yaml` (see example provided in the repository).

4. Run the crawler:
   ```bash
   python search.py
   python settings.py
   ```

## Output Structure

- `/结果文件/csv/` — Collected text data in CSV format
- `/结果文件/images/` — Downloaded and categorized images
- `/结果文件/videos/` — Downloaded and categorized videos

## Disclaimer

This tool is intended for academic research and complies with the terms of service of the respective platforms. Users are responsible for ensuring ethical and lawful use of the data.
This repository is based on an open-source project of the same name on GitHub. On top of the original code, I have implemented additional features, including proxy account support and the extraction of location and time information from the collected text data.
## Author

**Wang Lei**

I am an aspiring student with a strong passion for research and a keen desire to pursue a PhD offer. I am dedicated to advancing my academic journey and contributing to the field through innovative research and technical development.


## Contact

For questions, suggestions, or collaboration, please contact [2823115764@qq.com].
