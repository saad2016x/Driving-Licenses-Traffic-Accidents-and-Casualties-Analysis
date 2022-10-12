# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Local Traffic, Statistical Summaries and Inference

### Overview

Our first module in DSI covers:
- basic statistics (distributions, confidence intervals, hypothesis testing)
- many Python programming concepts
- programmatically interacting with files and directories
- visualizations
- EDA
- working with Jupyter notebooks for development and reporting

You might wonder if you're ready to start doing data science. While you still have **tons** to learn, there are many aspects of the data science process that you're ready to tackle. Project 1 aims to allow you to practice and demonstrate these skills.

For our first project, we're going to take a look at the number of traffic accidents and driving licenses issued in Saudi Arabia. We'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing the outcomes of traffic accidents in the various regions in Saudi Arabia.

Generally speaking, you will be asked to come up with a data science problem. Here's a specific prompt that should help you craft this statement:
> New traffic rules and fines were [implemented in October 2016](http://live.saudigazette.com.sa/article/164574/New-traffic-laws-in-15-days). As an analyst at the General Department of Traffic under the Ministry of Interior, you are a part of a team that tracks traffic accidents and gives policy recommendations that are best to help reduce injuries and casualties on the road. Your report should be geared toward **non-technical** executives with the General Department and you will use the provided data and outside research to make recommendations about how the General Department might work to reduce traffic accidents in a **region of your choice**.
---

### Datasets

#### Provided Data

For this project, you'll have two provided datasets:

- [Traffic Accidents and Casualties by Region](https://git.generalassemb.ly/DSI-MISK-VI/Project1/blob/master/data/saudi-arabia-traffic-accidents-2008.csv)
- [Driving Licenses Issued By Administrative Area](https://git.generalassemb.ly/DSI-MISK-VI/Project1/blob/master/data/saudi-arabia-driving-licenses-2004-2008.csv)

You can see the source for the accident data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/), and the source for the license data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/). **Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

#### Additional Data

Please refer to the website of the General Department of Traffic [here](https://www.moi.gov.sa/wps/portal/Home/sectors/publicsecurity/traffic/!ut/p/z1/04_iUlDg4tKPAFJABjKBwtGPykssy0xPLMnMz0vM0Y_Qj4wyizfwNDHxMDQx8nZ3CTQ1cAz0dvX3dDE2MnA00vfSj8KvIDg1T78gO1ARAHn-YJg!/) for further investigation into policies and other data that may be of interest. **You may use any data that you locate additionally.**


---

### Deliverables

All of your projects will comprise of a written technical report. As we continue in the course, your technical report will grow in complexity, but for this initial project it will comprise:
- A Jupyter notebook that describes your data with visualizations & statistical analysis.
- A README markdown file the provides an introduction to and overview of your project.
- A blog post in Arabic or English that showcases the problem and key findings of this project. More information will be given on this.

**NOTE**: Your entire Github repository will be evaluated as your technical report. Make sure that your files and directories are named appropriately, that all necessary files are included, and that no unnecessary or incomplete files are included.


---

### Technical Report Starter Code

Future projects will require you to decide on the entire structure of your technical report. Here, we provide you with [starter code](./code/starter-code.ipynb) in a Jupyter notebook that will help to guide your data exploration and analysis. **If you choose to edit the core structure of this notebook, make sure you don't exclude any of the requested operations**.

---

### Style Guide and Suggested Resources

[Here's an article](https://www.dataquest.io/blog/data-science-project-style-guide/) on style guide for data science projects using jupyter notebooks.

[Here's a concise tutorial](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook) on working with jupyter notebook.

[Here's a great summary](https://towardsdatascience.com/storytelling-with-data-a-data-visualization-guide-for-business-professionals-97d50512b407) of the main points of the book _Storytelling with Data_, which I can't recommend enough. [Here's a blog post](http://www.storytellingwithdata.com/blog/2017/8/9/my-guiding-principles) by the author about his guiding principles for visualizations.

[Here's a Medium story](https://towardsdatascience.com/thinking-of-blogging-about-data-science-here-are-some-tips-and-possible-benefits-680ff0e51d67) on data science blogging. [Medium](https://medium.com/) is a great platform for maintaining your blogging presence and follow authors you appreciate.
[Here's a blogpost](https://www.shoutmeloud.com/how-to-start-a-free-blog-using-blogspot-com.html) on blogging. [blogpost](https://blogspot.com/) is a also a great platform to use.
[Here's a caramella](https://www.shoutmeloud.com/how-to-start-a-free-blog-using-blogspot-com.html) on blogging. [caramella](https://caramellaapp.com) is an Arabic blogging platform you can use it as a choice when you start your blogging task.



---

### Submission

**Materials must be submitted by the beginning of class on TBD.**

Your technical report will be hosted on Github Enterprise. Make sure it includes:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis (renamed to describe your project)
- Data files
- Any other necessary files (images, etc.)


---


### Rubric
Your local instructor will evaluate your project (for the most part) using the following criteria.  You should make sure that you consider and/or follow most if not all of the considerations/recommendations outlined below **while** working through your project.

**Scores will be out of 18 points based on the 6 items in the rubric.** <br>
*3 points per section*<br>

| Score | Interpretation |
| --- | --- |
| **0** | *Project fails to meet the outlined expectations; many major issues exist.* |
| **1** | *Project close to meeting expectations; many minor issues or a few major issues.* |
| **2** | *Project meets expectations; few (and relatively minor) mistakes.* |
| **3** | *Project demonstrates a thorough understanding of all of the considerations outlined.* |

**Project Organization**
- Are modules imported correctly (using appropriate aliases)?
- Are data imported/saved using relative paths?
- Does the README provide a good executive summary of the project?
- Is markdown formatting used appropriately to structure notebooks?
- Are there an appropriate amount of comments to support the code?
- Are files & directories organized correctly?
- Are there unnecessary files included?
- Do files and directories have well-structured, appropriate, consistent names?

**Clarity of Message**
- Is the problem statement clearly presented?
- Does a strong narrative run through the project?
- Does the student provide appropriate context to connect individual steps back to the overall project?
- Is it clear how the final recommendations were reached?
- Are the conclusions/recommendations clearly stated?

**Python Syntax and Control Flow**
- Is care taken to write human readable code?
- Is the code syntactically correct (no runtime errors)?
- Does the code generate desired results (logically correct)?
- Does the code follows general best practices and style guidelines?
- Are Pandas functions used appropriately?
- Does the student demonstrate mastery masking in Pandas?
- Does the student demonstrate mastery sorting in Pandas?

**Data Cleaning and EDA**
- Does the student fix data entry issues?
- Are data appropriately labeled?
- Are data appropriately typed?
- Are datasets combined correctly?
- Are appropriate summary statistics provided?
- Are steps taken during data cleaning and EDA framed appropriately?

**Visualizations**
- Are the requested visualizations provided?
- Do plots accurately demonstrate valid relationships?
- Are plots labeled properly?
- Plots interpreted appropriately?
- Are plots formatted and scaled appropriately for inclusion in a notebook-based technical report?

**Research and Conceptual Understanding**
- Were useful insights gathered from outside sources?
- Are sources clearly identified?
- Does the student provide appropriate interpretation with regards to descriptive and inferential statistics?


### REMEMBER:

This is a learning environment and you are encouraged to try new things, even if they end up failing. While this rubric outlines what we look for in a _good_ project, it is up to you to go above and beyond to create a _great_ project. **Learn from your failures and you'll be prepared to succeed in the workforce**.
