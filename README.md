# youtube_extractor

A utility to extract YouTube video IDs from URLs.

## Installation

You can install the package using pip:

```
pip install youtube-extractor

```
## Usage


To use this package in your Python application, follow these steps:



Import the package

``` 
from youtube_extractor import extract_video_id_from_url

```




Extract Video ID from URL

```

video_url = 'https://www.youtube.com/watch?v=VIDEO_ID'
video_id = extract_video_id_from_url(video_url)

if video_id:
    print(f'Extracted YouTube Video ID: {video_id}')
else:
    print('Invalid YouTube URL')

 ```
Replace VIDEO_ID with the actual video ID you want to extract.

You can also use the package to extract video IDs from short URLs or YouTube Shorts URLs.

Example:


```
short_url = 'https://youtu.be/VIDEO_ID_SHORT'
video_id_short = extract_video_id_from_url(short_url)

if video_id_short:
    print(f'Extracted YouTube Video ID (Short): {video_id_short}')
else:
    print('Invalid YouTube Short URL')


 ```





Run your application, and you'll be able to extract YouTube video IDs from the provided URLs.


## License



This package is distributed under the MIT License. See the LICENSE file for more details.

## Issues and Contributions

If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository.

Contributions are welcome! Fork the repository, make your changes, and submit a pull request.


## Credits

This package was created by Super Nived.

## Support

For questions or support, you can reach out to  nivedchandran7@gmail.com




