# Dell Capstone -Predicting Technical Aptitude using Customer Conversations

Customer centricity lies at the heart of Dell Technologies. The objective of this project is to gain a deeper understanding of the customers seeking post-sale support. The project aims to specifically answer the following business questions –
- Is it possible to use the internal unstructured data sources to assess the technical aptitude of the customers?
- Is it possible to identify dominant customer groups to enable enhanced personalization of support services?

This project will help in developing targeted solutions for the customers, which will allow the customer service agents to provide effective solutions while providing quicker solutions to the problems.

Approximately 5GB of customer conversation data in the form of chat transcripts and emails between the customers and customer service agents was shared by the client sponsor team. The data belonged to the customers based in the United States and had been captured between Q1 and Q3 of FY2021. The data comprised of over one million unique chat transcripts, accompanied by additional data pertaining to the location, date and time of the conversation.

The student team manually labeled 300 chat transcripts due of the unavailability of prior labelled data. Some notable challenges faced by the team included dealing with anonymized and truncated transcripts, along with limitations on computing resources.

This project focuses on two different approaches for evaluating the technical aptitude of the customers. The first one capitalizes on TF-IDF methodology, which quantifies the importance of words in a document amongst a collection of documents. The second approach is based on word embeddings and neural networks.

TF-IDF approach resulted in an accuracy of approximately 61% while classifying customers as technically adept or otherwise, with a 41% correlation in the numeric scores. The neural network approaches, although more promising, were limited in terms of performance because of limited labelled data. For the scope of this project, the neural network-based approaches have been used only as a proof of concept.

The recommendations of the student team include the following –
- Increasing the character limit of the chat transcripts would help capture the information more accurately and yield more fruitful results.
- Augmentation of Labelled Dataset to improve the performance of neural network-based techniques, using services such as Amazon Mechanical Turks to manually label the data.

Please find below the details of the notebooks shared -
- "Exploratory Data Analysis.ipynb": Includes the exploratory data analysis conducted to understand the data scources better
- "TF-IDF Models.ipynb": Includes two models under TF-IDF approach - A) separating chat transcripts between agents and customers B) Considering entire transcripts
- "Neural Network Based Models.ipynb": Includes the Word2Vec, Neural Network (Classification and Regression) and Clustering Approaches
