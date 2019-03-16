# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Local Traffic, Statistical Summaries and Inference



### Traffic accetents & Driving leciesnes Analysis

#### Problem statemen

This project aims to help with tracks driving licenses issued in Saudi Arabia and traffic accidents and gives policy recommendations that are best to help reduce injuries and casualties on the road.





The project will examine trends in SAT and ACT participation rates, from 2017 to 2018, in order to identify states that demonstrate interesting trends in their participation rates. Additional research will be conducted on state policies that might influence these rates.

Contents:
You can see the source for the accident data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/), and the source for the license data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/). **Contents:**

#### Executive Summary
**Methodology:**
The project will examine trends in traffic accidents and driving licenses, in order to identify states that regions and time of accidents happened 

**Contents:**
**- Traffic accetents & Driving leciesnes Analysis :**
- Data Import & Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
<!-- Outside Research
Conclusions and Recommendation -->
 



Please refer to the website of the General Department of Traffic [here](https://www.moi.gov.sa/wps/portal/Home/sectors/publicsecurity/traffic/!ut/p/z1/04_iUlDg4tKPAFJABjKBwtGPykssy0xPLMnMz0vM0Y_Qj4wyizfwNDHxMDQx8nZ3CTQ1cAz0dvX3dDE2MnA00vfSj8KvIDg1T78gO1ARAHn-YJg!/) for further investigation into policies and other data that may be of interest. **You may use any data that you locate additionally.**

The project will examine trends in SAT and ACT participation rates, from 2017 to 2018, in order to identify states that demonstrate interesting trends in their participation rates. Additional research will be conducted on state policies that might influence these rates.
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

---

### Submission

**Methodology:**

Your technical report will be hosted on Github Enterprise. Make sure it includes:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis (renamed to describe your project)
- Data files
- Any other necessary files (images, etc.)


---


### Data dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|integer|Traffic_Accidents|The year when the accidents happened| 
|reigon|object|Traffic_Accidents|The cities or region of the accidents| 
|num_traffic_accidents|integer|Traffic_Accidents|The number of Traffic_Accidents happend| 
|latitude_accidents|object|Traffic_Accidents|This column present the latitude geographic coordinate of place the accidents| 
|longitude_accidents|object|Traffic_Accidents|This column present the longitude geographic coordinate of place the accidents| 
|num_accidents_result|object|Traffic_Accidents|Display the status of accidents| 
|accidents_result|object|Traffic_Accidents|The final status of the person how had an accients| 
|year|integer|Driving_Licenses|The year of driving licenses issued| 
|reigon|object|Driving_Licenses|The cities or region of driving licenses issued| 
|driving_licenses|integer|Driving_Licenses|The number of driving licenses| 
|latitude_accidents|object|Driving_Licenses|This column present the latitude geographic coordinate of place the driving licenses issued| 
|longitude_accidents|object|Driving_Licenses|This column present the longitude geographic coordinate of place the driving licenses issued| 


### REMEMBER:

This is a learning environment and you are encouraged to try new things, even if they end up failing. While this rubric outlines what we look for in a _good_ project, it is up to you to go above and beyond to create a _great_ project. **Learn from your failures and you'll be prepared to succeed in the workforce**.
