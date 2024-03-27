Getting Started

1. Make sure to place all of your images in a folder titles 'raws' in the same folder as the codes.
	- All Files should be labeled as 'Figure x. jpg'
	- the x should be replaced with a number
	- the file format of the figure does not matter
2. Collect all of the Captions and place them into a folder called 'captions'.
	- Place each caption into the 'captions' folder.
	- Each caption should be placed into a .txt file that is titled the same as the figure it corresponds.
	- If you are getting errors when processing captions, it is likely that the caption has a special character that cannot be processed. Find the special character and remove it.

Necessary Libraries

- cv2
- Pillow
- Numpas
- Pandas
- Plotly
- Matplotlib.pyplot
- pathlib
- os
- scipy
- sklearn
- umap
- kaleido

Output Folders

- The Figure Outputs Folder
	- Automiatically generated
	- Holds and of the Figures that are generated from the code and includes all histograms, all minimum and maximum figures, and all Dimensinality Reduction Figures
- The Gauge Charts Folder
	- Contains all of the Gauge Charts for Each of the figures showing where they measure on the criteria
- The Output Files Folder
	- Contains all of the final output files of the codes that does not need to be combined.
	- This includes: the Binary Extreme Labels; the TSNE, PCA, and UMAP Labels; the combined class Labels; the combined data fro mthe spreadsheets folder; the combined data fro mthe spreadsheets folder with labels; the total labels after consensus; amd the labels with the suggestions after all codes are run.
- The Spreadsheets Folder
	- Contains all of Sreadsheets of the found criteria seperated as different spreadsheets

Visual Count Differences(Code 04)

- In the event that you have counted the Visualization Count of all of the figures ahead of time, then you can use the Chi-Squared Analysis attatched to the Code 04 to see how different the code was to the manually counted visualizations.
- The excel file must be placed in the same folder as all of the codes
- The excel file must be titled 'testDataManualVizCount.xlsx' in order to be found be the code.
- The Excel file must have two columns titled 'Figure Number' followed by 'Visualization Count'
- The numbers must be titled by increasing alhpanumeric numbers for figure nubmers.
	- For example, it should increase as 1 --> 10 --> 11 --> 12... etc.
- The Figure Number columns should include the names of the figure files exactly as placed in the raws folder without their file extension. The manually counted visualization counts should be placed next to the proper figure name. 

-You can use the Chi-Squared section of the code by removing the three apostrophes from the section of the code.
- Otherwise, you can keep the apostrophes there without consequence.