# Manipulating thousands of data files for time series analysis

In the used dataset, there are 4000 text files each containing recorded data on an optical channel for 14 months with granularity of 15 minutes. Group of files (channels) belong to some specific optical link or segment. 

I grouped/merged all the files belonging to some specific segment while preserving the information of channel (i.e., channel number). The information about channel and segment numbers is available in the file names so we have to extract this information also. After that, I seperated date and time and plotted data for one particular channel.

The dataset used for this code is a public dataset by Microsoft and can be found here:

https://www.microsoft.com/en-us/research/project/microsofts-wide-area-optical-backbone/




