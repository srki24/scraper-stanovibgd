For this project I gathered some real estate data myself and made a simple regression model to predict prices.

For data gathering, I built a scraper using BeautifulSoup and Requests. It is working as of Feb.09.2021.

The scraper itself is slow, it load around 2 pages per second on my computer.
There are 20 observations on each page, and mumber of pages to scrape should be adjusted in the code itself.
For my model I used 50 pages of data, or 1000 observations.


Using gathered data, I have made a simple regression model to predict prices of real estate. 

For this part of the project I realied on modules: Pandas, Seaborn, Matplotlib and SKlearn.

The model explains around 60% of price variation, which is nothing impressive, and certainly could be improved (maybe a task for a further project?)

While building the model I have documented steps I've made in order to clean and preprocess data.



In this repository, I have included two Jupyter notebooks as separate files, one for the scraper and other for modeling.
I also included the data I have built my model upon.
