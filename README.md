# Shannon Fano
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<br>
A small practice library created as a project to encode an image.

### Installation
```
pip install shannon-fano
```
### How to use this?
This library returns the shannon fano code words of the image.
```
from shannon_fano import Shannon_fano_encoding

# enter the image name as <name of the image.extension>

image_name = Shannon_fano_encoding(input("Enter the Filename:"))
print(image_name.encode())
```
