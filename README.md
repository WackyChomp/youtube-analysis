# youtube-api



<!--
*******QUICK COMMANDS*******
. venv-yt/Scripts/activate
pip freeze > requirements.txt

https://developers.google.com/youtube/v3/quickstart/python
pip install google-api-python-client
py -m pip install --upgrade google-api-python-client

pip install pandas
-->


<!-- PROJECT LOGO -->

<br />
<div align="center" id='readme-top'>
  <a href="https://github.com/WackyChomp/youtube-analysis">
    <img src="https://media.tenor.com/6TwUFuzcjOQAAAAd/youtube.gif" alt="YouTube-Gif-Tenor" width="200" height="150">
  </a>

  <h3 align="center">YouTube Analysis</h3>

  <p align="center">
    Discover current trends and hidden statistics
    <br />
    <a href="https://github.com/WackyChomp/youtube-analysis"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/WackyChomp/youtube-analysis">View Demo</a>
    ·
    <a href="https://github.com/WackyChomp/youtube-analysis/issues">Report Bug</a>
    ·
    <a href="https://github.com/WackyChomp/youtube-analysis/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


## About The Project
<p>The amount of content on YouTube is unfathomable. Every second there's a new video uploaded and cementing itself into YouTube's video sharing plaform. Underneath the visual frontend rubble lies meta data that is overlooked by the majority.

Fortunately for us, the developers at YouTube have an API service which allows us to interact directly with YouTube's data behind the scenes. 

<br>

<u><b>Project Purpose / Vision:</b></u>

* Analyzing modern trends and content creators by manipulating raw data extracted from YouTube API with <u>Pandas</u> library
* Prototyping with <u>Jupyter Notebook</u> develop automated analysis
* Creating data visualizations with <u>Matpotlib</u> and <u>Seaborn</u> to illustrate video and channel statistics
* Generating word cloud to identify word/phrase frequency of video titles
* Utilizing Natural Language Processing (NLP) to gauge user sentiment by analyzing user comments
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Built With
Here are the tools used:

* [![python][python]][python-url]
* [![jupyter][jupyter]][jupyter-url]
* [![youtube][youtube]][youtube-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<br>



<!-- GETTING STARTED -->
## Getting Started

Setup is kept at a minimum for immedate usage locally!

### <u>Installation</u>

1. Login with your gmail account into "Developer Console" to obtain a free YouTube API Key at --- [https://developers.google.com/youtube/v3/docs](https://developers.google.com/youtube/v3/docs)
2. Clone the repo:
   ```sh
   git clone https://github.com/WackyChomp/youtube-analysis.git
   ```
3. Create Python virtual environment in the root directory:
    ```
    python -m venv INSERT_PROJECT_NAME
    ```
   Activate the virtual environment with:
   ```
   . INSERT_PROJECT_NAME/Scripts/activate
   ```
4. Install all packages from requirements.txt:
   ```
   pip install -r requirements.txt
   ```
5. Create `.env` file and enter your API key:
   ```
   YOUTUBE_API_KEY = ENTER YOUR API KEY HERE :)
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<br>

## Getting started w/ Visual Studio Code
```
** git clone <insert_repo>

** 

** 

** 

** 

** 

** 
```

<br>

## Something

<br>

## Tasks / Goal Posts
- [X] Created prototype to scrape video statistics of one channel
- [] Created prototype to scrape video statistics of multiple channels
- [X] Created dataframe with YouTube API
- [X] Created data visualizations
  - [X] Bar Graph
  - [X] Word Cloud
  - [] Etc.
- [] Automate process
- [] Finalize README.md

<br>

## Title
![description goes here](./)

## Title
![description goes here](./)



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

List of helpful resources for inspiration and point you into a direction!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Python](https://www.python.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [YouTube API Docs](https://developers.google.com/youtube/v3/docs)
<!--* []() -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[python]:https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white
[python-url]:https://www.python.org/

[jupyter]:https://img.shields.io/badge/Jupyter-20232A?style=for-the-badge&logo=jupyter&logoColor=orange
[jupyter-url]:https://jupyter.org/

[youtube]:https://img.shields.io/badge/YouTube_API-FF0000?style=for-the-badge&logo=youtube&logoColor=white
[youtube-url]:https://www.youtube.com/