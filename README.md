# Non-alcoholic-beer
A repository for some of the work I'm doing for my capstone practicum of my graduate school. Currently, I am working on a project to make data-driven perceptual map. To collect the data, I scraped reviews and ratings from a beer forum called Beer Advocate.

The goal of this exercise for me personally is to classify the NA beer offerings of a retailer. The idea is to see how many types of NA beer products does the retailer carry and the find the relative positioning of each on a 2D plot. The perceptual map will be very helpful in understanding the portfolio of the retailer. This information can be invaluable to a company trying to create an effective sales pitch to the retailer in the future.

Currently, I am reading this article: [A novel approach for dimension reduction using word embedding: An enhanced text classification approach](https://www.sciencedirect.com/science/article/pii/S2667096822000052#:~:text=Dimensionality%20reduction%20refers%20to%20techniques,improve%20the%20learning%20algorithm's%20efficiency). Another piece that I have read is [Perceptual mapping of hotel brands using online reviews: a text analytics approach](https://link.springer.com/article/10.1007/s40558-015-0033-0). Both of these should be useful.

A video tutorial about PCA and Perceptual Mapping can also be useful, which is [Perceptual Mapping using Principal Component Analysis](https://www.youtube.com/watch?v=oyrmyLaMKik) by Prof Manisha Malik.

I used R and Python for the scraping work. Some packages I used are listed below

* R: \{Tidyverse\}, \{rvest\}, \{reticulate\}, \{factoextra\}
* Python: Requests, BeautifulSoup4

The entire project so far has allowed me to work on my web scraping, data manipulation, and principal component analysis skills.

I've included code for the PCA based on the ratings people left for the NA Beers. This is the PCA visualization for the 20 competing NA Beers
