## Data Challenge

Data is just more fun when we can play with it and relate with it? Well, we say yes! That is precisely how we challenge our data analysts. We want to find great people to come join our team developing products across our business. There are many approaches to work with data, and we expect data to be innovative, enabling the creation of data solutions. For that, you need Data Management, as real-world data is more often than not a bit messy. We always must be ready to handle and create understanding of data throughout its lifecycle. Business Intelligence is also crucial, as we need to assist business empowerment via self-service data tools and visualizations.

This challenge is your next step in showing what you can do. Be hands-on and, during the next 5 days, submit a working data product. In your submission, be sure to include:
- Working code with documentation
- Documentation of metadata and data quality: what have you found here?
- Visualizations of key insights

Show your data skill!

## Problem Statement

Keep Financial is a regional bank headquartered in Washington, DC, and has branches in nearby states. Seeking to grow, Keep's leaders want to test if entering the home loans market is a good strategy. They first need to understand the region’s market.

Your partners have directed your team to the Home Mortgage Disclosure Act (HMDA) dataset collected and published each year by the federal government. The dataset has basic data on all home loan applications. The data is available for analysis in support of public policy (HMDA History), providing a valuable source of information about the target market.

To help answer questions about the loans market, particularly the "Conventional/Conforming" loans market, you’ve to create the first iteration to plan the work ahead.

## Instructions

Realize that this is real-world imperfect data. We recommend planning for about 8 hours to complete this Data Challenge. Be the judge of the quality of your work submitted; it is not timed. Remember, there is no right answer. If you get stuck, decide based on your best judgment, make documented assumptions, and keep going.

We are looking for you to show your data skills. For that, we have assigned three areas at a basic level. After that, you’ve got the freedom to turn it into your own product with your own personal touch and direction.

1. **Data** – Using functions, load the data. Your team will use it for that purpose, and it needs to be easy.
    - Merge the application data with institution data such that each loan application is assigned a "Respondent_Name". Additionally, create a new attribute that buckets "Loan_Amount_000" into reasonable groups.
    - Provide a simple API of two functions:
        - `hmda_init()` – Read the data files and return a pointer or object containing the expanded HMDA data from part a.
        - SQL – Write the following queries based on the tables provided:
            1. In the same view, show the rank of the agencies based on loan amount and rank by number of parent zip codes where they have provided loans.
            2. Show the three largest loan amounts per county and the average of the county (repeated for each loan amount).

2. **Quality** – Wrong data is worse than no data at all.
    - Perform a quality assessment on those `Loan_Amount_000` and `Respondent_Name`. Do not stop at descriptive analytics; produce guidelines or techniques for quality checks that can be applied.
    - What other attributes (1 or 2) are relevant to keep regular quality checks, and why?
    - Document your comments and guidelines; these would be conversation topics at our next chat.

3. **Create a Visual Narrative with Data** – If you had 20 minutes to present your findings and learnings, what would you show? Create visuals to illustrate some of your insights. Charts and plots must be generated from your code; do not submit them using Excel, Power BI, or Tableau-like software. Have you thought of a Jupyter document?
    - Provide a hypothesis to enter a new geography and elaborate on that.
    - Visualize metrics for market size by state and year; provide a business explanation for what the chart shows or explains and whether your hypothesis is proved, disproved, or if you need additional data.
    - Show key insights based on visualizations.

4. **Go a Step Further** – What has piqued your mind so far? Any worries about data quality? Make hypotheses, prototype a tool to improve this data product, and highlight your area of expertise. Here are some questions to help you out:
    - What if quality was interactive and automated? Clean outliers, e.g., census tract-by-tract checking for all tracts, extend your code with functionality to fix them.
    - Take the analytical route. Identify clusters of lending patterns, e.g., geographies, that represent markets where we want to market similar products.
    - Interaction is always cool, can it work here? Can you create an interactive experience for your team to see and analyze the market share in a given geography?

## Data and Tools

Do not develop on software that requires a license, not even with a free trial period. Use open-source software like Python, R, or JavaScript if you will.

### Data Inputs
- `2012_to_2014_loans_data.zip`
- `2012_to_2014_institutions_data.zip`

### Documentation
- `HMDA Data Challenge and Expectations.docx`
- `Data_Challenge_Technical_Considerations.html`
- `Data_Challenge_Metadata.html`
- `2013guide.pdf` (Guide to the data)

### Tools
Show us how you tackle business problems using programming tools; spreadsheet-based analysis is not allowed. You can mix programming languages, but make them be in sync. Our preference is R and Python, which are commonly used in our team. However, we don’t want to impose; if your strong skill is in another open-source programming language, go ahead!
