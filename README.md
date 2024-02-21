# Data Scientist

#### Technical Skills: Python, R, SQL, Power BI, Tableau, Excel


## Education

MSc. Data Science and Analytics | University of Leeds, UK | _Sep 2021 - Sep 2022_

BTech. Chemical Engineering | Heritage Institute of Technnology, IN | _Aug 2014 - Jun 2018_


## Work Experience
**Data Scientist 2 @ Sagentia Innovation | Epsom, UK | _Oct 2022 - Present_**
- Automated the process of updating chemical odourants to an existing excel-based database using Pandas and Openpyxl libraries in Python which reduced manual updation by 90%.
- Converted an Excel-based database into structured format (SQL) to assist in data retrieval. Created report on beverage odour profile using Power BI.
-	Screened 1800+ patents and 2300+ academic papers to determine their topic with 98% accuracy using NLP. 
-	Consulted on the application of Gen AI for discovery of small molecules. 

**Data Science Intern @ Flip Robo Technologies | Remote | _Apr 2023 - Oct 2023_**
-	Performed Web Scraping using Beautiful Soup and Selenium for data collection. 
-	Conducted data pre-processing, cleaning, and wrangling to prepare data for modelling.
-	Identified, analysed, and interpreted trends in complex datasets using supervised and unsupervised learning.
-	Developed predictive models to solve problems such as employee attrition and success of marketing campaigns.
-	Created effective visualisations to communicate complex technical concepts to stakeholders.

**Senior Software Engineer @ Infosys Limited | Mysore, IN | _Nov 2018 - Sep 2021_**
-	Led the development and testing of real-time web applications belonging to various domains using Java, Spring Boot, Spring Data, Spring REST API, Angular, MySQL, JUnit, Git and Jenkins using Agile scrum methodology.
-	Created and reviewed learning content on Java, Spring Boot and Microservices that spans around 100 learning hours.
-	Trained and assessed new recruits in programming languages like Java and Python.


## Projects
### Recommender Systems: Implementation and Evaluation

<a href="https://www.mrs.org.uk/blog/gkb/recommender-systems-implementation-and-evaluation"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/file-lines.svg" width="20" height="20"></a>
<a href="https://github.com/aindrilabasu/recommender_systems"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20" height="20"></a>
<a href="https://www.youtube.com/watch?v=dZoYuuXFdkE"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/youtube.svg" width="20" height="20"></a>

Developed a recommendation engine as a product for a fashion retailer, through the use of a combination of content-based and collaborative filtering algorithms and customer and product data, including historical customer transactions. Identified the best item recommendation strategy for the retailer by developing various recommender systems based on the same dataset but using different (technical and marketing) strategies and comparing them to each other. Demonstrated how the generated recommendations can be aligned with the business and marketing strategies of the retailer to promote specific products.

![Recommender Systems](/assets/img/cb-cf.png)

### Generating Image Captions using an Image to Text Model

<a href="https://github.com/aindrilabasu/image-caption-generation"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20" height="20"></a>

Worked with an image to text model to understand the principles of text-pre-processing and vocabulary building using a subset of COCO dataset used for image caption generation. Used two different text similarity metrics like Bleu Score and Cosine Similarity for evaluation of the model.

The basic principle of the image-to-text model is an Encoder network which encodes the input image as a feature vector by providing the outputs of the last fully-connected layer of a pre-trained CNN (ResNet-152). The pretrained network has been trained on the complete ImageNet dataset and is thus able to recognise common objects.
These features were then fed into a Decoder network along with the reference captions. As the image feature dimensions are large and sparse, the Decoder network includes a linear layer which downsizes them, followed by a batch normalisation layer to speed up training. Those resulting features, as well as the reference text captions, were passed into a recurrent network (we use an RNN).

The training was made more efficient by decoupling the encoder and decoder networks

![Image Caption Generation](/assets/img/encoder_decoder_diagramv2022.png)

### Predicting Cancer Mortality Rates in US Counties

<a href="https://github.com/aindrilabasu/cancer-mortality-prediction"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20" height="20"></a>

Predicted cancer mortality rates in "unseen" US counties using several regression techniques. Apart from basic Linear Regression model, regularised models like Lasso and Ridge Regression and bagging model like Random Forest was also implemented. The models were evaluated based on their RMSE scores. Implemented cross-validation to improve the accuracy of the models. Finally the model with the least RMSE score was used on the test data to predict the cancer mortality rates.

![Cancer Mortality Prediction](/assets/img/cancer.jpg)

<br>

### Investigating how the age of serial killers at the time of thir first offence varies with their motives

Analysed a subset of the serial killer dataset from Radford/FGCU serial killer database after cleaning and feature engineering. Both numerical and graphical summaries were explored for the significant variables: Age at first kill, Age at last kill and Career duration. The relationship between these variables were then established and parameters of the proposed models were estimated using Method of Moments Estimator. Then the distribution for each of the motives (Anger, Convenience, Enjoyment or power) was studied to determine the type of test to be used for hypothesis testing.

The intial hypothesis that the mean age of first kill is 27 years was rejected for all motives after conducting the respective tests. The comparison of different populations was performed using two-sample hypothesis test by considering a pair of motives. While it was concluded that the Age at First Kill was not the same for "Anger" and "Enjoyment or power" motives (by rejecting the null hypothesis), for the motives "Anger" and "Convenience" as well as "Convenience" and "Enjoyment or power", we failed to reject the null hypothesis.

![Serial Killer](/assets/img/serial-killer.jpg)


