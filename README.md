# GeoQuest

[![PyPI - Version](https://img.shields.io/pypi/v/geoquest.svg)](https://pypi.org/project/geoquest)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/geoquest.svg)](https://pypi.org/project/geoquest)

-----

## Search, Geocode, and Reverse-Geocode Locations

GeoQuest is a lightweight Python package that provides an easy-to-use interface for searching, geocoding, and reverse-geocoding locations. With support for various APIs (including
Nominatim), it's perfect for location-based services, address validation, and route planning.


## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Features

* Search for locations by address or other criteria

### Planned enhancements
* Geocode addresses into latitude/longitude pairs
* Reverse-geocode coordinates back into human-readable addresses
* Caching mechanism to improve performance and reduce API requests

## Installation

You can install GeoQuest using pip:
```console
pip install geoquest
```

## Environment Setup
To get started, please follow these steps:

### Step 1: Create a copy of the configuration template

1. Copy the `.example.env` file from this repository into your project directory.
2. Rename the copied file to `.env`
3. Save the renamed file.

### Step 2: Update the configuration values

1. Open the newly created `.env` file in a text editor.
2. Replace `YOUR_API_KEY_HERE` with your actual API key.
3. Review and update any other configuration options as needed.

### Step 3: Save and commit the updated file

1. Make sure to save the updated `.env` file.
2. Commit the changes to a version control system like Git.

### Example

Here's an example of what the updated `.env` file might look like:
```makefile
# Environment Variables Configuration

OPEN_CAGE_API_KEY="YOUR_API_KEY_HERE"
```
By following these steps, you'll have a properly configured environment for running this project. If you have any issues or questions, feel free to reach out to us!

## API Documentation

For a full list of available functions and their usage, please refer to the [API documentation](https://mohitshrestha.github.io/geoquest/).

1. Get County Details by manually entering city and state
2. Get County Details by loading CSV file that contains city and state

### Get County Details by loading CSV file that contains city and state

#### Step 1: Make sure to update the csv file `city_state_input_data.csv` with desired combination of city, state info. The file is inside the folder `data/raw/`.

## Contributing

If you'd like to contribute to GeoQuest or report any issues, feel free to open a pull request or issue on this repository.

## License

`GeoQuest` is distributed under the terms of the [MIT](https://github.com/mohitshrestha/geoquest/blob/main/LICENSE) license.

MIT License

Copyright (c) 2024-present Mohit Shrestha <contact@mohitshrestha.com.np>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
