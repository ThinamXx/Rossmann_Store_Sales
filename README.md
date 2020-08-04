# [**Rossmann Store Sales**](https://www.kaggle.com/c/rossmann-store-sales/overview)

**Fastai Library or API**
- [Fast.ai](https://www.fast.ai/about/) is the first deep learning library to provide a single consistent interface to all the most commonly used deep learning applications for vision, text, tabular data, time series, and collaborative filtering.
- [Fast.ai](https://www.fast.ai/about/) is a deep learning library which provides practitioners with high-level components that can quickly and easily provide state-of-the-art results in standard deep learning domains, and provides researchers with low-level components that can be mixed and matched to build new approaches.

**Description**
- Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

**Preparing the Model**
- I have used [Fastai](https://www.fast.ai/about/) API to train the Model. It seems quite challenging to understand the code if you have never encountered with Fast.ai API before.
One important note for anyone who has never used Fastai API before is to go through [Fastai Documentation](https://docs.fast.ai/). And if you are using Fastai in Jupyter Notebook then you can use doc(function_name) to get the documentation instantly.

**Getting the Model**
- Since, It is one of the Competition from Kaggle. I have preapared the Data for this Project from [Kaggle](https://www.kaggle.com/c/rossmann-store-sales/data)

**Model**
- I have used Fastai API which is short and so powerful in its Implementation. If you have gone through the Data, you would see that all the Data are tabular, so I have used Tabular Learner API in this Project. The API is shown below:

```javascript
tabular_learner(data, layers=[1000, 500], ps=[0.001, 0.01], emb_drop=0.04,
                        y_range=y_range, metrics=exp_rmspe)
```

- The Tabular Model is given below:

![Image](https://res.cloudinary.com/dge89aqpc/image/upload/v1596542079/Tabu_ogebyc.png)
