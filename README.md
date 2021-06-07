# Fake News Detection

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/voiculaura/

The datasets used in this project are open source and freely available online. The data includes both fake and truthful news articles from multiple domains. The truthful news articles published contain true description of real world events, while the fake news websites contain claims that are not aligned with facts. 

Steps:

- Exploratory data analysis and data pre-processing: functions needed to process all input documents and texts like data cleaning, tokenizing, stemming, etc. including exploratory data analysis and topic modelling sections.

- Feature extraction and selection methods from sci-kit learn python libraries. For feature selection, I have used methods like simple bag-of-words and n-grams and term frequency like tf-tdf. 

- Build all the classifiers for predicting the fake news detection. The extracted features are fed into different classifiers. I have used Naive-bayes, Logistic Regression, XGBoost, CNN and LSTM. Performance metrics: accuracy, f1 score, AUC-ROC, confusion matrix. 


## Contributing

I use this for my own projects, I know this might not be the perfect approach for all the projects out there. If you have any ideas, just [open an issue][issues] and tell me what you think.

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

## License

Distributed under the MIT License. See `LICENSE` for more information.
