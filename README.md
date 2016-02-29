flickr-downloader
============

sudo apt-get install python-flickrapi python-pip
sudo pip install pyprind joblib eventlet

Please create a new file flickr_api_key.py by copying
flickr_api_key_EXAMPLE.py and pasting your Flickr API key and secret.

Scripts:
- download_dataset: downloads a number of images for a set of queries.

Example download:
- python download_dataset.py bla 10 -query "kilimanjaro"

Notes:
- max number of images is not working
