# remove_duplicate_image
Removing multiple Images by using Python Script and Hashing.

Medium:
<https://medium.com/@urvisoni/removing-duplicate-images-through-python-23c5fdc7479e>

## Usage
```
duplicate_image_remove.py [-h] [-s] dir

positional arguments:
  dir           directory containing duplicate images

optional arguments:
  -h, --help    show this help message and exit
  -s, --slient  remove images without confirmation
```

## Example
```
./duplicate_image_remove.py "~/Pictures/" -s
```

## Dependency
Please check `requirements.txt`.  
`pip install -r requirements.txt`  
Install `python-tk` if virtual enviroment is used.
