![header](github_resources/header.jpg)

# **Overview**

This projects consists on designing a functional webpage showcasing a project I did, the original project repository is [here](https://github.com/JuanjoFernandez/python-api-challenge) and the deployed page is hosted at [GitPages](https://juanjofernandez.github.io/Web-Desing-Challenge/index.html)

# **Webpage functionality**

- The page is built using a combination of html, css, and [bootstrap](https://getbootstrap.com/)
- The page is mobile friendly by taking advantage of the bootstrap grid and css media queries
- Index.html acts as a landing page with a brief explanation of the project
- The website consists of several visualizations obtained by analyzing data obtained from [OpenWeather API](https://openweathermap.org/)
- The data page is obtained by exporting a pandas dataframe to html, the code for that is located on this [Jupyter Notebook](assets/csv_to_html.ipynb)

# **Repository structure**
````bash
│   .gitignore
│   bootstrap.min.css
│   commits.md
│   correlations.html
│   data.html
│   index.html
│   LICENSE
│   maps.html
│   README.md
│   style.css
│   tempcloud.html
│   temphumi.html
│   templat.html
│   tempwind.html
│
├───assets
│   │   csv_to_html.ipynb
│   │   header.jpg
│   │   home.jpg
│   │   map1.png
│   │   pandas_html.html
│   │   weather_data_1619635358.csv
│   │
│   └───plot_images
│           cloud_lat.png
│           hemi_cloud_lat.png
│           hemi_humi_lat.png
│           hemi_temp_lat.png
│           hemi_wind_lat.png
│           hum_lat.png
│           map.png
│           map1.png
│           temp_lat.png
│           wind_lat.png
│
└───github_resources
        header.jpg
````