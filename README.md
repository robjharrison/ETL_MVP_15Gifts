# ETL_MVP_15Gifts

#O2 Product Set ETL Pipeline
This is an MVP ETL pipeline which extracts a product set from O2, one of our clients, and transforms and stores this data into a clear and understandable format.

# Project Overview
The task was to create an ETL pipeline to extract handset devices, pay monthly tariffs, and optionally sim-only tariffs from the O2 website. The pipeline was built using Python and Jupyter notebooks.

## Approach
To approach this task, I first went through a purchase journey on the O2 website to get a feel for how the website operates. I then used web scraping techniques to extract the relevant product data from the website. The data was then cleaned and transformed to a clear and understandable format, and stored in a CSV file.

## Data Sources
The product data was sourced from the O2 website, specifically the phones page (https://www.o2.co.uk/shop/phones). The data was extracted using the BeautifulSoup library in Python.

## MVP Output
The MVP output produced by the ETL pipeline is a CSV file containing a subset of the products available on the O2 website, including handset devices, pay monthly tariffs, and optionally sim-only tariffs. The output file is included in this GitHub repository.

## Future Improvements
- Expand the data captured to include additional product attributes such as colour, capacity, availability, and features.
- Store the data in a scalable and business-oriented manner, such as a data lake or cloud storage.
- Have the ETL pipeline code reviewed by others, and ensure that it is built with consideration for existing frameworks and best practices.
- Conduct a deeper scrape of the O2 website to extract deeper and additional value from the process, including optional sim-only tariff data.
- Conduct further optimisation tests to improve run-times and ensure the pipeline can scale with larger data sets.
- Explore the potential for cross-client(s) application of the pipeline.
- Consider non-client/3rd party data enrichment to provide more in-depth data than customer-facing/simplified web page data sources. However, this raises other issues that must be considered.
- Expand the Pipeline reporting by including at least price data in the identify_outliers() function.
- Ensure that the MVP is indeed what was requested/expected by stakeholders, and not just 'what I think/my interpretation' of the brief.
- Remove the use of user-defined scrap depth and develop a more dynamic approach to scraping data.
- Decide whether outliers are to be removed or only identified and flagged with a reason, and update the pipeline accordingly. The presentation can also be accessed at [insert link here].

# Contact
For any questions or feedback, please contact robjharrison@gmail.com
