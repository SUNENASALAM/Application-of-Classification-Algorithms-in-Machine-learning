# KNN And Decision Tree ALgorithm Classification
Have classified the dataset called “Wine_Quality_Red” determining the quality of red wine through different levels of content in it. The feature considered as the dependent variable in order to do the classification is “qual” (describing the quality of the red-wine) 
--> considered the dataset called “wine_quality_red”. 
The dataset consists of red wine data specifically referring to the feature "quality" stating the quality of it (categorical - 0 - (at most quality red wine) and 1 - (at least quality red wine). Due to privacy and logistic issues, only physiochemical (inputs) and sensory (the output) variables are available. (e.g., there is no data about the grape types, wine brand, wine selling price etc.,) Hereby providing the detailed information of the main features of the dataset. 

## Feature name and description:

### fixed acidity	(numerical)
Is used to describe the total concentration of acids that are difficult to evaporate. Because they don't alter much during the fermentation and aging stages of winemaking, these acids are known as fixed acids.

### volatile acidity (numerical)
Alludes to the wine's volatile acid content, especially the presence of acetic acid. It's one of the chemical parameters winemakers look at to determine how stable and good a wine is. Although a wine's overall flavor profile benefits from volatile acidity, too much of it can be unfavorable.
### citric acid	(numerical)
It is a red wine supplement. Citric acid is a tool used by winemakers to control the acidity levels in wine, especially in areas where grapes may naturally have less acidity than desired.

### residual sugar (numerical)	
Is used to describe the quantity of sugar left in the wine after the fermentation process is finished.

### chlorides	(numerical)	
speaks of the amount of chloride ions present in the wine. Wine's flavor and aroma can be affected by the presence of chloride, a negatively charged ion. Wine's chloride content is commonly expressed in parts per million (ppm) or milligrams per litre (mg/L).

### free sulfur dioxide	(numerical)
refers to the sulfur dioxide (SO2) that is present in the wine but is not bound, conjugated, or reactive. To stop oxidation and microbial deterioration, sulfur dioxide is frequently added to wine. Because of its dual antibacterial and antioxidant qualities, it is an important tool for winemakers to preserve wine quality.

### total sulfur dioxide (numerical)
measurement that reflects the total amount of sulfur dioxide in the wine, both bound and free forms. In winemaking, sulfur dioxide serves as an antioxidant and preservative. It assists in halting the oxidation and microbiological activity that cause wine to deteriorate.

### density	(numerical)
relates to the wine's mass per unit volume. Common units of measurement are grams per milliliter (g/mL) or comparable ones. Temperature, alcohol content, sugar content, and composition are some of the variables that affect wine's density.

### pH (numerical)
It is a gauge for alkalinity or acidity. It's a pH scale that goes from 0 to 14, where lower numbers represent acidity and higher values represent alkalinity. A pH of 7 is regarded as neutral.

### sulphates	(numerical)
refer to the family of chemical compounds known as sulfur dioxide and its different forms, which are compounds that combine sulfur and oxygen.

### alcohol	(numerical)
Red wine's alcohol content is commonly stated as an alcohol by volume (ABV) percentage. During the fermentation process, which produces carbon dioxide and alcohol from the sugars in grape juice, wine is made. Wine's alcohol content varies according to ripeness of the grapes, conditions during fermentation, and winemaking techniques.

### quality	(numerical)
refers to the general traits and qualities that establish the wine's quality or grade.

# HOW TO RUN THE CODEBASE:
To run a file saved in IPython Notebook (.ipynb) format, you have several options depending on your preferred environment. Here are the common methods:

## Jupyter Notebook or JupyterLab:

If you have Jupyter Notebook or JupyterLab installed, you can open your terminal or command prompt, navigate to the directory where your .ipynb file is located, and then run either of the following commands:

### jupyter notebook your_file.ipynb
This will open a web browser window with the Jupyter interface, allowing you to run and interact with the code in your notebook.

## VSCode (Visual Studio Code):
If you are using Visual Studio Code with the Python extension installed, you can simply open the .ipynb file in VSCode. The extension provides support for Jupyter notebooks, and you can run the code cells directly within the VSCode interface.

## Google Colab:
If you want to run the notebook in the cloud, you can use Google Colab. Open Google Colab in your web browser, go to File -> Open Notebook, and upload your .ipynb file. You can then run the code cells in the Colab environment.

## nbviewer (View Only):
If you only need to view the contents of the notebook without executing the code, you can use nbviewer (https://nbviewer.jupyter.org/). Paste the link to your notebook or upload the file, and nbviewer will render a static version for viewing.

Choose the method that best fits your workflow and the tools you have available. The Jupyter ecosystem provides flexibility, and you can choose between local or cloud-based environments based on your requirements.
