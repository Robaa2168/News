# News 

News is a web application that displays a list of various news sources. On choosing a news source, it will preview the top news articles of the day. Clicking a news article will redirect the user to read it fully from the news source. It achieves this by using the News API.

## Author

[ROBERT_ KIPKOECH](https://github.com/Robaa2168/News.git)

## Description
News is a web application that displays a list of various news sources. On choosing a news source, it will preview the top news articles of the day. Clicking a news article will redirect the user to read it fully from the news source. It achieves this by using the News API.

## User Stories
As a user I would like:
* to see various news sources and select the ones I prefer
* to see all the news articles from that news source
* to see the image, description and time the news article was created.
* to click on an article and read it fully from the news source.

## Specifications
| Behavior        | Input           | Outcome  |
| ------------- |:-------------:| -----:|
| Display News sources | N/A | List of various News sources is displayed |
| Articles from selected News source | **Click** a News source | Directed to a page with a list of articles from the selected source |
| Display image, description, title and date of publish | N/A | An articles image, title, description and date of publication are displayed |
| Read an entire article | **Click** on an article | Directed to the source's site to read the entire article |

## Prerequisites
* Python3.9

## How to use 
* Click /) <br/>
  
* Click any News source you'd like


## Setup/Installation 
* git clone https://github.com/Robaa2168/News.git
* $ cd News
* $ python -m venv virtual (install virtual environment)
* $ source virtual/bin/activate
* $ python -m pip install -r requirements.txt (install all dependencies)
* Inside the manage.py module change the config_name parameter from 'production' to 'development' ie app = create_app('production') should be app = create_app('development')
* $ ./start.sh

## Contact Information 
Email  me at [robertlagat38@gmail.com]

## Known Bugs

No known bugs

## Technologies Used
- Python3.9
- Flask framework
- Bootstrap

## License
* *MIT License:*
* Copyright (c) 2020 **ROBERT KIPKOECH**