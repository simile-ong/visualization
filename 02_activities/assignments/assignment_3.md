# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify:

    # VISUALIZATION 1
    # Toronto Police Service's Proposed 2025 Budget: Top 10 Units with Highest Budget for Stationery and Office Supplies

    > What software did you use to create your data visualization?

    Python (matplotlib).
        I used it to generate a horizontal bar graph.

        I obtained my dataframe from the City of Toronto's Open Data (https://open.toronto.ca/dataset/toronto-police-budget/).

    * Note: If I had more time, I would have used Seaborn instead because it would have allowed me to play around with the data a little more.

    > Who is your intended audience?

    Anyone who is interested in examining the Toronto Police Service (TPS)'s annual budget.
    
    > What information or message are you trying to convey with your visualization? 
    
    The top 10 units in Toronto Police Service (TPS) with the highest amount of money allocated to the spending category "Stationery and Office Supplies."

    The user can alter my code to compare other spending categories, and/ or include more/ fewer units in the graph.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?

    The original dataset is very overwhelming because it contains 7689 lines of information, so I tried to generate a graph that is relatively easy to understand (i.e. lower cognitive load on the user).

    I opted for a horizontal bar graph so that the unit names are more visible, and the graph remains readable in case the user wants to include more units/ bars.

    I also added labels indicating the values of each bar to make the graph easier to interpret.
    
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    I worked programmatically to create the graph, which makes my visualization reproducible when the user runs my code. I also made sure to mention the source of my data so that the user can download the CSV file and run my code.
    
    I used quite a few variables with verbose and descriptive names so users can edit the code to suit their needs. As such, I believe my code is also reusable and replicable too.


    > How did you ensure that your data visualization is accessible?  
    
    I added labels and included a markdown at the top of the notebook to explain the code to the user.

    > Who are the individuals and communities who might be impacted by your visualization?  
    
    Torontonians who are finding out how the TPS is spending their taxpayer dollars. Also the TPS and Toronto City Coucil.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    As mentioned above, the original dataset is very overwhelming, so I isolated what I felt would be the most pertinent information (i.e. unit names, categories of spending (i.e. Cost_Element_Long_Name) and amount).

    I chose the spending category "Stationery and Office Supplies" because it is a line item that doesn't seem significant but nevertheless amounts to quite a lot of taxpayer dollars.

    Obviously the graph is quite basic but hopefully that makes the dataset more approachable.

    > What ‘underwater labour’ contributed to your final data visualization product?

    I'm not sure if this question is referring to the underwater labor behind the collection of the data or labor I put in, so I'll try to answer both.

    For the dataset (i.e. TPS 2025 Budget), someone had to collect data from the various branches of the TPS and collate them in a single CSV file. Someone also had to upload the data to the Open Data Toronto Catalogue.

    For the final data visualization product, I benefited from the education I received from the instructors and TAs of the course!


    # VISUALIZATION 2
    # HOW MUCH DOES TORONTO POLICE SERVICE SPEND ON PENCILS?

    > What software did you use to create your data visualization?
    
    Tableau Public.
        I haven't published my work onlin because it's unfinished. Please let me know if there are any issues opening my workbooks!

    > Who is your intended audience?
    
    Anyone who is interested in examining the Toronto Police Service (TPS)'s annual budget

    > What information or message are you trying to convey with your visualization?

    I am trying to make it easier for users to examine different categories in the TPS's budget across different units and across different years.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?

    As mentioned above, I tried to make the visualizations as easy to understand as possible. It was more challenging to do so on Tableau, especially as I tried to make use of the platform's functionality to offer the user more information on the dataset.

    As mentioned above, I preferred using horizontal bar graphs to ensure unit names are more visible and that the graph remains readable even with numerous units/ bars. Additionally, I opted for a line graph to clearly demonstrate trends over time. I didn't experiment with too many types of visualizations to make it easier for the user to absorb the data. (This probably makes my visualizations less interesting to look at.)

    I added labels where I thought it made sense to make the graphs easier to interpret even if doing so makes the visualizations a little busier.

    I tried to keep the visualizations as clean as possible, though I made the horizontal bars on the first page pencil colored to make the graph more interesting.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?

    I'm not sure if my visualizations on Tableau are reproducible, which menas it may be harder for the user to verify if they are accurate. However, my visualization aims to spark the user's curiosity about the TPS's budget, ideally leading them to examine the raw data themselves.

    > How did you ensure that your data visualization is accessible?

    I added labels to the visualizations and a short description explaining the project.

    > Who are the individuals and communities who might be impacted by your visualization?

    Torontonians, TPS, Toronto City Council.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization?

    For my Tableau visualizations, I compiled the TPS budgets from 2020 to 2025, which were in separate CSV files. I chose to do so to make it easier to compare data across time. This meant I had a lot of data to work with, so I focused on a few key elements of the collated dataset (i.e. year, budget type [i.e. proposed vs. approved vs. actual] unit names, categories of spending [i.e. Cost_Element_Long_Name] and amount).

    As mentioned above and in the description of the project, I chose an inconspicuous spending category ("Stationery and Office Supplies") to encourage the user to examine other categories that may be overlooked. This information is displayed on the main dashboard so the user can interact with simpler visualizations to get a sense of the point of the project and familiarize themselves with its format.

    > What ‘underwater labour’ contributed to your final data visualization product?

    (Repeating my answer above)
    For the dataset (i.e. TPS 2025 Budget), someone had to collect data from the various branches of the TPS and collate them in a single CSV file. Someone also had to upload the data to the Open Data Toronto Catalogue.

    For the final data visualization product, I benefited from the education I received from the instructors and TAs of the course!

    I also had to compile the 2020 to 2025 CSV files and edit a few unit names to ensure consistent naming conventions across the different years of data. (e.g. I changed "People & Culture" to "People and Culture.") If I had more time, I would have standardized the naming conventions of spending categories and created more visualizations (perhaps of greater complexity).


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09/05/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
