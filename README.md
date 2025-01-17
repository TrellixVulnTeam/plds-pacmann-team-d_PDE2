# **PLDS PACMANN Team D**
## **Predicting live-birth occurrence before in-vitro fertilization treatment**
### **Background**
Infertility is a global health issue and is estimated to affect 48.5 million couples worldwide. For this reason, the demand for in vitro fertilization (IVF) is increasing with over 2.5 million cycles being performed every year, resulting in over 500,000 deliveries annually. However, the whole process of IVF treatment is very time consuming and very expensive with no guarantee of success. Given the consequences, a tool to predict the probability of a successful live birth before an IVF treatment is importantly needed for patients' counseling and shaping their expectations about the treatment outcome. 
### **Objectives**
* Main objective of this task is to predict the live-birth occurence before in-vitro fertilization treatment.
* Methods that we use in this task is Decision Tree.
### **Methods**
![Architecture Overview-Overview (1)](https://user-images.githubusercontent.com/72263498/181916886-585c1ba4-1a0c-4537-acab-edd20fb62572.jpg)
#### **Training**
![Architecture Overview-Training](https://user-images.githubusercontent.com/72263498/181915379-91baf13b-39ea-46c1-85a9-0e4a9ff74c37.jpg)
#### **Prediction**
![Architecture Overview-Predict (1)](https://user-images.githubusercontent.com/72263498/181916893-6f608d9e-9a2f-409d-ae8a-1350cb94eae9.jpg)
### **How to Run**
Click https://rifkimputra-plds-pacmann-team-d-appsrcapp-k85nzw.streamlitapp.com/  
### **Dataset**
* Data IVF 2010-2014
* Data IVF 2015-2016
### **Conclusion**
* The Decision Tree model with hyperparameter tuning has shown the best result, achieving an ROC score of 0.652 and F1-score of 0.4892 when compared with other models. 
* The results we have obtained so far have not been satisfactory. For further improvement, we suggest exploring more models such as SVM, deep learning, or KNN. Adding more important predictors, such as consumption of alcohol, smoking, caffeine consumption, hypertension, and other lifestyle factors that have a significant impact on predicting pregnancy, might be beneficial as well to improve the result.
* The EDA feature in the app could be improved to make the charts live-updated as more data is input through the application.
### **References**
1. Mascarenhas, M. N., Flaxman, S. R., Boerma, T., Vanderpoel, S., & Stevens, G. A. (2012).
National, regional, and global trends in infertility prevalence since 1990: A systematic analysis of
277 Health Surveys. PLoS Medicine, 9(12). https://doi.org/10.1371/journal.pmed.1001356
2. Fauser, B., 2019. Towards the global coverage of a unified registry of IVF outcomes.
Reproductive BioMedicine Online, 38(2), pp.133-137. https://doi.org/10.1016/j.rbmo.2018.12.001
3. Braat, D., Schutte, J., Bernardus, R., Mooij, T. and van Leeuwen, F., 2010. Maternal death related
to IVF in the Netherlands 1984-2008. Human Reproduction, 25(7), pp.1782-1786.
https://doi.org/10.1093/humrep/deq080
4. Inhorn, M. and Patrizio, P., 2015. Infertility around the globe: new thinking on gender, reproductive
technologies and global movements in the 21st century. Human Reproduction Update, 21(4),
pp.411-426. https://doi.org/10.1093/humupd/dmv016
5. Jeni, L. A., Cohn, J. F. and De La Torre, F., 2013. Facing Imbalanced Data--Recommendations for
the Use of Performance Metrics. Humaine Association Conference on Affective Computing and
Intelligent Interaction, pp. 245-251, doi.org/10.1109/ACII.2013.47.
6. Goyal, A., Kuchana, M., Ayyagari K. P. R., 2020. Machine learning predicts live‑birth occurrence
before in‑vitro fertilization treatment. Scientific Reports,
https://doi.org/10.1038/s41598-020-76928-z

