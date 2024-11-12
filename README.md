### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 05-09-2024
### AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
![364791167-ed15f97c-090e-459f-9b57-32c1e6a0797f](https://github.com/user-attachments/assets/0591bbff-76e7-425b-8351-cd5742caacbb)
![364792168-501c9e02-ad00-4abf-8c81-7a82fa2b3bc5](https://github.com/user-attachments/assets/219f9e6a-da47-40e2-9ceb-eddb48087453)
![364792060-79ec5581-aa13-4d0e-be9f-342ec9c49cac](https://github.com/user-attachments/assets/519cac1f-905a-48b5-8fb8-0322d8d7d056)
![364792593-fabff075-09a7-4dd1-bb9f-09185282b1d4](https://github.com/user-attachments/assets/566cb22b-b27f-4b8c-9016-2618c19b8f7a)


### Result:
Thus, sentimental analysis for the given data using Rapidminer is done successfully.
