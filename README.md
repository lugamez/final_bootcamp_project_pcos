# Final bootcamp project - Polycistic Ovary Syndrome (PCOS)

Repository to store data for the final bootcamp project - Topic: PCOS

# Purpose of the study

Polycystic Ovary Syndrome (PCOS) is a prevalent hormonal disorder affecting 8–13% of reproductive-aged women globally, yet up to 70% remain undiagnosed. It stands as the primary cause of anovulation and a leading contributor to infertility, significantly impacting physical and emotional well-being. Characterized by hormonal imbalances, irregular menstrual cycles, excess androgen levels, and ovarian cysts, PCOS poses challenges for fertility and is often associated with a spectrum of long-term health issues. Symptoms include irregular periods, infertility, acne, excessive hair growth, and weight gain. Furthermore, individuals with PCOS face an increased risk of developing conditions such as type 2 diabetes, hypertension, high cholesterol, heart disease, and endometrial cancer. Diagnosis typically involves the identification of specific symptoms and ultrasound findings, with treatment options aimed at managing symptoms rather than providing a cure. With this study, we aimed to explore models for early and simple diagnosis of PCOS to enhance the quality of life of affected women.

# Dataset selected

The dataset was downloaded from Kaggle.com (https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos) and it contains dat collected in 10 different hospitals across the city of Kerala in India. 

# Questions and findings

Our goal was two-fold: firstly, to gather general information about the health of women of reproductive age, and secondly, to develop machine learning models that could predict whether a woman is likely to have PCOS or not.

Among our findings, we discovered:

A notable surge in PCOS cases among women in their late 20s and early 30s.
The AMH hormone emerges as a robust predictor of PCOS.
Women with PCOS are more likely to experience weight gain, skin darkening, and excessive hair growth compared to those without these symptoms.
Even the most basic regression models demonstrate remarkable accuracy in predicting PCOS.
The top-performing models employ oversampling techniques to address class imbalances in the target variable.
Key features such as the number of follicles, skin darkening, and hair growth exhibit significant importance in explaining the predictive model.

# Next steps

Following a comprehensive analysis of the dataset and an exploration of the correlations among its variables, we have unearthed significant insights into the health profiles of women affected by PCOS.

The integration of data from diverse geographical regions is vital for a comprehensive assessment of PCOS across populations, reducing biases, and enhancing our comprehension. This endeavor lays a stronger groundwork for future research efforts.
Further experimentation with alternative models and the application of advanced boosting techniques present promising avenues for improving predictive performance, potentially enhancing our ability to discern and address PCOS-related health concerns effectively.

# Limitations of the study

The dataset comprises information collected from hospitals in Kerala, India, offering insights into a subset of the population. It's important to note that this sample represents a distinct demographic with unique characteristics compared to broader global populations. Therefore, the conclusions of this study are merely limited to the dataset used and they don't represent the full spectrum of the world population.

# List of references

1. PubMed Central (2021). "AI and Machine Learning Can Successfully Diagnose Polycystic Ovary Syndrome." (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10137609/)

2. Johns Hopkins Medicine (n.d.). "Polycystic Ovary Syndrome (PCOS)." (https://www.hopkinsmedicine.org/health/conditions-and-diseases/polycystic-ovary-syndrome-pcos)

3. World Health Organization (2021). "Polycystic Ovary Syndrome (PCOS)." (https://www.who.int/news-room/fact-sheets/detail/polycystic-ovary-syndrome)

4. Bahceci (n.d.). "What is HCG? What does Beta HCG Values Mean?" (https://bahceci.com/en/what-is-hcg-what-does-beta-hcg-values-mean/)

5. National Institutes of Health (2021). "AI, Machine Learning Can Successfully Diagnose Polycystic Ovary Syndrome." (https://www.nih.gov/news-events/news-releases/ai-machine-learning-can-successfully-diagnose-polycystic-ovary-syndrome)

6. Advanced Fertility (n.d.). "AMH Fertility Testing." (https://advancedfertility.com/infertility-testing/amh-fertility-testing/)

7. Center for Human Reproduction (n.d.). "Interpreting Your Levels." (https://www.centerforhumanreprod.com/contents/understanding-infertility/female-infertility/interpreting-your-levels)

8. Medical News Today (n.d.). "Normal LH Ranges and What They Mean." (https://www.medicalnewstoday.com/articles/324122#normal-lh-ranges-and-what-they-mean)

9. Healthline (n.d.). "Hypothyroidism: Effects of Hypothyroidism." (https://www.healthline.com/health/hypothyroidism/effects-of-hypothyroidism#Other-systems)
