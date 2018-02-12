Training progress exploratory analysis

R script prepared for exploratory analysis of cognitive training (dual n-back) behavioral data in the course of 6-week training (18 sessions). Data were obtained for my PhD project: "Temporal dynamics of functional connectivity changes induced by cognitive training" in which participants were fMRI scanned four times during intensive working memory training.


Input of the sctript:
- .txt files with information about maximum n-back level for each session (18 sessions, 22 trials each)-separate file for each subject

Script: 
- merges .txt files with training progress information for each subject
- organizes data for exploratory analyses
- calculates mean and maximum n-back level for each session, each subject 
- generates scatter plotts with general progress for all subjects (mean and maximum n-back level)
- fits regression line for individual learning progress data (stores individual intercept and slope values)
- generates interactive line plot for individual progress data (plotly)
- generates histograms for intercept and slope variables

Required libraries: ggplot2, plotly
