# YouTube Channel Data Collection

This tool allows you to collect metadata about all videos from a specified YouTube channel using the YouTube Data API v3. The collected data is saved in a parquet file.

## Setup

Before running the script, you'll need to obtain an API key from [Google Cloud Console](https://console.cloud.google.com/).

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/harsh24924/youtube-channel-data-collection.git
    cd youtube-channel-data-collection
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the script:**
    ```bash
    python3 main.py
    ```

2. **Follow the prompts:**
    *   You will be asked to enter your YouTube Data API Key.
    *   Then, enter the YouTube Channel ID.

## Output

Once the script finishes execution, the collected video data will be saved to `data.parquet`.
This file will be located in the same directory where you ran the `main.py` script.
