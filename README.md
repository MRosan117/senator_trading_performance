# Senator Trading Performance

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name=" Rental-Market-Data-San-Fran"></a>
<img src="https://github.com/Nievz/Project_One_Draft/blob/main/Images/Banner.png">

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://github.com/Nievz/Project_One_Draft/blob/main/Images/senate logo.png" alt="Logo" width="200" height="200"> 
  </a>

<h3 align="center">Senator Trading Performance</h3>

  <p align="center">
    This project analyzes and publishes the public transaction information of members of Congress and Senators in the United States, focusing specifically on their trades in company shares around the world. The data reveals which politicians have vested interests in particular stocks and provides insight into which positions have increased or decreased.
    <br />
    <a href="https://github.com/github_username/repo_name">
  </p>
</div>




<!-- ABOUT THE PROJECT -->
## About The Project

<img src="https://github.com/Nievz/Project_One_Draft/blob/main/Images/ezgif.com-gif-maker.gif" alt="Logo" width="1000" height="250">
  <p align="center">
    The purpose of this analysis is to determine whether Senators' portfolios tend to outperform the market as a whole. We analyze the investments using open-source data to determine if they support the notion that senators use their informational advantages for personal gain.
Several US senators who traded stocks during their terms saw significant gains in their portfolios. The concern is that, despite publicly implying otherwise, these senators traded in anticipation of news that would have a significant impact on financial markets. 
  </p>
  <p align="center">
    We used data from Senators' common stock purchases and sales, as well as the date and approximate value of the transactions, for this analysis. We only consider assets not held in qualified blind trust because Senators do not report holdings or transactions on any assets held in qualified blind trust. Our data does have some limitations; for example, we cannot calculate the magnitude of profits earned by individual senators. Senators only report transaction dollar volumes within broad ranges. If we had more time we would use the same complete process to analyze similar data from the House of Representatives. 

  </p>

  <p align="center" style="display: flex;" >
<img src="https://img.shields.io/npm/l/express" />
<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/tyleradammartinez/SIG-Dashboard-Application" />
</p>

## Required Python Libaraies

### CALCULATIONS
`pip3 install pandas` <br>
`pip3 install numpy` <br>
`pip3 install matplotlib` <br>
`pip3 install plotly` <br>
### APIs
* **[YFinance](https://pypi.org/project/yfinance/ "pypi yfinance Project Page")** | *Market data*

<!-- GETTING STARTED -->
## Data and Research Design

### Senators' By State

  <p align="center">
    In this section of the analysis, we add geospatial data and use interactive visualizations with hvPlot and GeoViews to investigate the data's relationships. We construct our map using a modified DataFrame that combines Senators' locations with state coordinates.
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/Map.png"> 

### Transactions by State

  <p align="center">
    We explore the transactions carried out by senators on a by party basis using an interactive visualization the data in the form of a bar chart. We construct our bar chart utilizing Opensource data, which includes the transaction data pertaining to Senators.
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/bokeh_plot(1).png"> 

### Transactions by Political Party'

  <p align="center">
    Using an interactive visualization in the form of a bar chart, we investigate the transactions carried out by senators on a state-by-state basis. We construct our bar chart utilizing Opensource data, which includes the transaction data pertaining to Senators.
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/senate_plot.jpg"> 

### Investment By Industries

  <p align="center">
    For this section of the analysis, we calculate the investments by industry using numerical and visual aggregation, and then visualize the results as a bar chart. 
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/industry.png" width="900" height="900"> 

### Box Plot
<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/box.png"> 

### Heatmap

  <p align="center">
    For this section of the analysis, we use a heatmap as a graphical representation of data that was used to represent Senators' excess return, using a color-coding system to represent different timeframes.
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/heatmap.png">

### Prerequisites

In order to complete this analysis successfully, you will first need to set up the environment in which Python will be developed. More specifically, this analysis calls for the following:
* Pandas
  ```sh
  pip install pandas
* npm
  ```sh
  npm install npm@latest -g
  ```
* matplotlib
  ```sh
  python -m pip install -U pip
  python -m pip install -U matplotlib
  ```
* matplotlib
  ```sh
   pip install plotly_express==0.4.0
  ```
* YFinance
  ```sh
   pip install yfinance
  ``` 

### Installation

1. Install NPM packages
   ```sh
   npm install
   ```
2. If you get the error 'pip' is not recognized as an internal or external command, use the python -m command when installing yfinance.`
   ```js
   python -m pip install yfinance
   python3 -m pip install yfinance
   py -m pip install yfinance
   ```


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.




<!-- CONTACT -->
## Contact

Project Link: [https://github.com/MRosan117/senator_trading_performance/tree/main](https://github.com/MRosan117/senator_trading_performance/tree/main)




<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [https://senatestockwatcher.com/]()
* [https://finance.yahoo.com/]()
* [https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md]()
* [https://holoviz.org/tutorial/Interlinked_Plots.html]()
* [https://holoviz.org/tutorial/Interactive_Pipelines.html]()
* [https://hvplot.holoviz.org/user_guide/Pandas_API.html]()
  



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
