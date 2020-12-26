# Amazon
## 1) Amazon food reviews
Context  
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

Contents  
Reviews.csv: Pulled from the corresponding SQLite table named Reviews in database.sqlite
database.sqlite: Contains the table 'Reviews'

Data includes:  

Reviews from Oct 1999 - Oct 2012  
568,454 reviews  
256,059 users  
74,258 products  
260 users with > 50 reviews  

for data link : https://www.kaggle.com/snap/amazon-fine-food-reviews?select=Reviews.csv  

## 2) Toy Products on Amazon

Context  
This is a pre-crawled dataset, taken as subset of a bigger dataset (more than 115k products) that was created by extracting data from Amazon.com.

Content  
This dataset has following fields:  

product_name  
manufacturer - The item manufacturer, as reported on Amazon. Some common "manufacturers", like Disney, actually outsource their assembly line.
price  
number_available_in_stock  
number_of_reviews  
number_of_answered_questions - Amazon includes a Question and Answer service on all or most of its products. This field is a count of how many questions that were asked actually got answered.  
average_review_rating  
amazon_category_and_sub_category - A tree-based, >>-delimited categorization for the item in question.  
customers_who_bought_this_item_also_bought - References to other items that similar users bought. This is a recommendation engine component that played a big role in making Amazon popular initially.  

description  
product_information  
product_description  
items_customers_buy_after_viewing_this_item  
customer_questions_and_answers - A string entry with all of the product's JSON question and answer pairs.  
customer_reviews - A string entry with all of the product's JSON reviews.  
sellers - A string entry with all of the product's JSON seller information (many products on Amazon are sold by third parties).  

Acknowledgements  
This dataset was created by PromptCloud's in-house web-crawling service.  

Inspiration  
This detailed dataset can be used to answer questions like:  

What types of toys are most popular on Amazon?  
How dominant are brands in the Amazon toy market?  
Can you break down reviews to analyze their sentiment and contents?  

## 3) Amazon Job Skills  

Context  
I always wanted to know what qualifications are required for getting hired as a software developer in Amazon. So, I decided to do a small project, scraping Amazon job portal at https://amazon.jobs. So I scraped all of the job data from that site by going every job page using Selenium and BeautifulSoup packages. I only take Job Title, Job Location, Job posting date, Job responsibilities, minimum and preferred qualifications for Software Development role.  

I will put the Jupyter notebook including all my codes in my Github repository and everyone can extract the same info for other job roles at Amazon.  

Content  
This dataset is collected using Selenium and BeautifulSoup by scraping all of the jobs for Amazon job site.  

Title: The title of the job  

location: Location of the job  

Posting_date : Posting date of the job  

DESCRIPTION: Overall description for the job  

BASIC QUALIFICATIONS: Minimum Qualifications for the job  

PREFERRED QUALIFICATIONS: Preferred Qualifications for the job  

Acknowledgements  
This dataset is collected using Selenium and BeautifulSoup packages. This product uses the Amazon job site.  

Inspiration  
1) You can find most popular skills for Amazon software development Jobs  
2) Create similar job posts  
3) Doing Data Visualization on Amazon jobs (My next step. Stay tuned!)  
