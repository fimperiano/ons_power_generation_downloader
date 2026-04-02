# ONS Power Generation Downloader

This repository contains a Python script designed to automatically download power generation data by power plant from the ONS cloud service and save the files locally.

## Overview

The objective of this project is to automate the collection of electricity generation data made available by the Brazilian National System Operator (ONS). The script connects to the ONS cloud source, downloads the available files related to power generation by plant, and stores them in a local directory for later use in analysis, monitoring, or data processing workflows.

## Features

- Automatic download of generation data by power plant
- Local storage of downloaded files
- Organized and reproducible data collection process
- Suitable for periodic execution and future automation

## Purpose

This project was created to support data collection tasks involving the Brazilian power sector. By automating the download process, it reduces manual effort, improves consistency, and helps maintain an updated local database of ONS generation files.

## Expected Workflow

1. Access the ONS cloud service
2. Identify the target files related to power generation by plant
3. Download the files automatically
4. Save them to a local folder
5. Repeat the process whenever new data becomes available

## Repository Status

This project is currently under development.

## Possible Future Improvements

- Scheduling automatic daily or weekly downloads
- Logging download history
- Verification of new or updated files only
- Data preprocessing after download
- Integration with databases or cloud storage solutions

## Technologies

- Python
- Requests / HTTP libraries
- File system handling with Python standard libraries

## Notes

This repository focuses on automating data retrieval from ONS public cloud resources. Users should verify the data source structure and access conditions before execution, as source URLs or file organization may change over time.

## Author

Developed for automated collection of ONS power generation data by power plant.

