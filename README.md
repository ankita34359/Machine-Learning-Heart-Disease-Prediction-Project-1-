𝐇𝐞𝐚𝐫𝐭 𝐃𝐢𝐬𝐞𝐚𝐬𝐞 𝐏𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐨𝐧 𝐌𝐨𝐝𝐞𝐥



𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄

This project aims to predict the 10-year risk of coronary heart disease (CHD) using a machine learning approach. The model is trained on a dataset containing various demographic, behavioral, and medical features. The goal is to accurately classify patients as either at risk or not at risk for CHD within the next 10 years.

𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗦𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲

• Heart Disease Model.ipynb: Jupyter notebook containing the full data exploration, preprocessing, model training, evaluation, and selection process.
• heart.py: Streamlit web application script that allows users to input data and predict the risk of heart disease based on the trained model.
• heart_disease_data.csv: The dataset used for training and evaluating the models.
• best_model.pkl: The saved machine learning model (using joblib) that provides predictions in the Streamlit app.


𝗧𝗮𝘀𝗸𝘀 𝗣𝗲𝗿𝗳𝗼𝗿𝗺𝗲𝗱

𝟭) 𝗗𝗮𝘁𝗮 𝗘𝘅𝗽𝗹𝗼𝗿𝗮𝘁𝗶𝗼𝗻 𝗮𝗻𝗱 𝗦𝘁𝗮𝘁𝗶𝘀𝘁𝗶𝗰𝗮𝗹 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀:

Explored the dataset, handled missing values, and calculated statistical measures.

𝟮) 𝗔𝗹𝗴𝗼𝗿𝗶𝘁𝗵𝗺 𝗦𝗲𝗹𝗲𝗰𝘁𝗶𝗼𝗻:

Selected suitable machine learning algorithms for the task, including Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and Gradient Boosting.

𝟯) 𝗗𝗮𝘁𝗮 𝗣𝗿𝗲𝗽𝗿𝗼𝗰𝗲𝘀𝘀𝗶𝗻𝗴:

Normalized continuous variables, encoded categorical variables, and split the dataset into training and testing sets.

𝟰) 𝗠𝗼𝗱𝗲𝗹 𝗧𝗿𝗮𝗶𝗻𝗶𝗻𝗴:

Trained multiple models and evaluated their performance based on accuracy, precision, recall, and F1 score.

𝟱) 𝗠𝗼𝗱𝗲𝗹 𝗘𝘃𝗮𝗹𝘂𝗮𝘁𝗶𝗼𝗻:

Compared the models using precision, recall, and F1 score. Selected the best-performing model based on a balance between these metrics.

𝟲) 𝗠𝗼𝗱𝗲𝗹 𝗦𝗮𝘃𝗶𝗻𝗴:

Saved the best-performing model using joblib for future use.

𝟳) 𝗦𝘁𝗿𝗲𝗮𝗺𝗹𝗶𝘁 𝗪𝗲𝗯 𝗔𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻:

Developed a Streamlit app (heart.py) that allows users to predict their risk of heart disease by inputting relevant features.

𝟴)𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁 𝗼𝗻 𝗚𝗶𝘁𝗛𝘂𝗯:

Uploaded the Jupyter notebook, trained model, Streamlit app, and dataset to GitHub for public access.


𝗖𝗼𝗻𝗰𝗹𝘂𝘀𝗶𝗼𝗻

This project demonstrates a comprehensive approach to predicting heart disease using machine learning. The Streamlit app provides an easy-to-use interface for users to predict their heart disease risk based on input features. And creates some plots or graphs like 𝗽𝗶𝗲 𝗰𝗵𝗮𝗿𝘁, 𝗯𝗮𝗿 𝗽𝗹𝗼𝘁 𝗮𝗻𝗱 𝗯𝗼𝘅 𝗽𝗹𝗼𝘁.
