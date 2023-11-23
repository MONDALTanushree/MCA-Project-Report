# MCA-Project-Report
Detecting Unwanted Messages: A PySpark NLP approach for Ham-Spam Filtering

The present study endeavours to tackle the ever-growing problem of email spam through the development of an advanced Ham Spam Email Detection system. Leveraging cutting-edge machine learning and natural language processing techniques, we aim to empower users with a robust and accurate tool that can automatically identify and filter spam emails, thus enhancing their overall email experience.

**Key Objectives of the present Study involves:**

•	Data Collection and Preprocessing: Our initial step involves gathering a diverse dataset of labelled emails, comprising both HAM and SPAM categories. We will meticulously preprocess the data, cleaning and structuring it to ensure optimal performance during model training.

•	Feature Engineering: Extracting meaningful features from emails is crucial for building an effective classification model. We will explore various techniques to represent emails in a format that best captures their distinguishing characteristics.

•	Machine Learning Model Selection: To achieve accurate classification, we will evaluate and compare several machine learning and/or natural language processing algorithms. The chosen model / algorithm will be fine-tuned to attain optimal performance.

•	Model Evaluation: Rigorous testing and cross-validation of the trained model will be performed to assess its accuracy, precision, recall, and score. We aim to achieve a well-balanced model that minimizes false positives and false negatives.

•	Integration and Deployment: The ultimate objective is to create an easy-to-use email plugin or standalone application that integrates seamlessly with popular email clients, making it accessible to a wide range of users.

**The proposed filtering system shall be carried out by use of the following technologies:**

The Core technology of the study would be PYSPARK (combination of Python with Apache Spark) and Math Plot (Python API for drawing accuracy scatter plot graph). Entire software / application shall be designed to run in Cloud Computing platforms. In this study / project, Google Colab shall be used. The Cross-platform compatibility shall be achieved by Python which is running on top of Java Virtual Machine. The speed of execution would be achieved by the artificial intelligent tool PYSPARK which is running on top of the popular distributed file system HADOOP Ecosystem and YARN Resource manager.

It is proposed that the end user may use this software in two ways – they can use the saved trained model to get spam prediction or once in a while, re-process the entire program and save a new model. By doing this apart from the initial historical dataset used for training, new data is also added with historical data. The AI model would identify new patterns during reimbursed learning with new data.

The proposed salient feature would be that the user can update the model with new data without incurring any additional cost. The model would be designed and developed using the top-down approach methodology. Entire software shall be divided into Python functions and each function would be called using appropriate Menus. This would eliminate duplication of codes again and again.

The login program would be designed in such a way that it incorporates all the security features laid down by Google Gmail Account. Using this the user can recover forgotten passwords or user id’s, they can create new users to share the model. When user execute the login program, control is transferred to Gmail Authentication Dialogue window.

The end user would be able to inject new data with the help of a text editor or using excel worksheets. The model would automatically convert encoding to ‘ANSI’ standard text. SMS messages can also be added using text editors.

From company’s dedicated websites, copying each mail to text editor is a tedious job. To overcome this the user can extract emails directly by using Python API - ‘BeautifulSoup’, then transfer it into this model.
