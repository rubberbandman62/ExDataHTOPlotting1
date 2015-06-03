H1 Exploratory Data Analysis - Week 1 Course Project

This is my solution to the course project of week 1:

loadData.R - loads the relevant data and store it after transforming the date
time strings to POSIXct in hpc.csv. subsequent calls to loadData.R just load
hpc.csv. All the scripts plot[i].R ([i] in {1,2,3,4}) first call loadData.R and
then do the plotting.

plot1.R - plots the histogram of Global Active Power and stores it in plot1.png

plot2.R - plots the Global Active Poweragainst the date time and stores it in 
          plot2.png

plot3.R - plots the three sub metering values against the date time and stores
          in plot3.png

plot4.R - plots four graphs in in one canvas and stores it in plot4.png