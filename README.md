Data Pipeline 
        Web Scraping : Scrape book details such as title, price, rating availability, and category from Books to Scrape.
        Data Cleaning: Clean the scarped data and convert prices and ratings into proper numeric formats, and calculate the INR price.
        Database: Store the cleaned data in a normalized SQLite daStabase using primary and foreign keys.
        SQL and Pandas Analysis: Perform SQL queries and reproduce JOIN operations using Pandas for analysis.

Analytics: 
         EDA: Analyze the Titanic dataset using statistics, missing value analysis, outlier detection, and visualizations.
         Feature Engineering: Handle missing values encode categorical variables, and standardize numerical features.
         Machine Learning: Train Logistic Regression, Decision Tree, and Random Forest classification models.
         Model Evaluation:  Compare models using accuracy, precision,recall,F1-score,ROC-AUC, and apply techniques such as SMOTE and GridSearchCV.

Support Assistant:
        Document Embedding: Convert the eight provided policy documents into embeddings using Sentence Transformers.
        Vector Retrieval: Store embeddings in ChromaDB and retrieve the top 3 relevant documents for policy related question.
        LangGraph Workflow: Use intent classification and LangGraph nodes to route policy and general question.
        API and Mock LLM: Expose the assistant through a FastAPI
