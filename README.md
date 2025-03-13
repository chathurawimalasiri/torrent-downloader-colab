# Torrent Downloader for Google Colab

This repository contains a Jupyter Notebook that allows users to download torrents using `libtorrent` in Google Colab. It supports both magnet links and `.torrent` files and saves the downloaded content to Google Drive.

## Features
- Download torrents via **magnet links** or **.torrent files**
- Uses `libtorrent` for efficient peer-to-peer downloading
- Saves files directly to **Google Drive**
- Works seamlessly in **Google Colab**

## Installation
Since this script runs in **Google Colab**, you don't need to install anything locally. The required dependencies are installed within the notebook itself.

## Usage
1. Open the notebook in **Google Colab**.
2. Install `libtorrent` by running the first cell.
3. Mount Google Drive to save the downloaded files.
4. Enter a **magnet link** or upload a **.torrent file** when prompted.
5. The download will start automatically.

## Dependencies
- `libtorrent`
- `google.colab`
- `IPython`

## How to Run
1. Open Google Colab.
2. Upload and open the `torrents_download.ipynb` notebook.
3. Run all the cells in order.
4. Provide a magnet link or upload a `.torrent` file when prompted.

## Notes
- Ensure that you have sufficient storage in your **Google Drive**.
- Larger torrents may take longer to download depending on network conditions.
