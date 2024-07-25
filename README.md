# Invidious Cast

- Convert YouTube channel content into podcast RSS feeds via Invidious.
- Support for audio and video formats with customizable URLs.
- Automatic handling of iTunes-specific tags for improved compatibility.

## Usage
1. You can access channel feeds via: host[:5000]/channel?id=ID[&type=audio]
2. You can access playlist feeds via: host[:5000]/playlist?id=ID[&type=audio]

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
This project uses the following libraries:

Flask: https://flask.palletsprojects.com/
Requests: https://docs.python-requests.org/
xml.etree.ElementTree: https://docs.python.org/3/library/xml.etree.elementtree.html
