# Customer-Segmentation
## The problem statement here is that i have got a dataset consisting of details of customers of their transactions in a shopping mall, what i have to do is work with the data and segment the customers accordingly and submit the final results to the stakeholders.
## Getting started with the problem we see that the there is a lot of problems with the data such as the data we have recieved is in an encoded format so we had to further import appropriate libraries to access the data, but the problem does not end here moving ahead we see various other problems like duplicate data, null values etc in the data and to handle them we had to do a lot of data wrangling, simultaneously we also did EDA and found few interesting insights.
![Screenshot (64)](https://user-images.githubusercontent.com/116963622/215838303-77553780-bd9a-4467-9a6a-ef80c0dd3f5d.png)
![Screenshot (65)](https://user-images.githubusercontent.com/116963622/215838544-0c31c1a8-df41-4772-9b88-60d24baa624d.png)
![Screenshot (66)](https://user-images.githubusercontent.com/116963622/215838718-906af60e-59f4-4971-8c43-fe71abfedeec.png)
## After that it was time for me to get started with the segmentation process and their could have been multiple ways i could have gone by it, but being a business student i chose the RFM approach for segmentation which is a marketing approach to segment customers, what i did was assign scores to the customers based upon their recency that is how recently they visited and purchased from the mall, frequency that is how frequently they visited and purchased from the mall and monetary that is how much did they spend on the purchases, i assigned them scores out of 0 to 3 with 0 being the lowest tier and 3 being the highest tier, then i segmented them on the basis of their sum of the scores, and the individual scores put together as an id.
![Screenshot (67)](https://user-images.githubusercontent.com/116963622/215841830-a2030703-935c-4843-9568-d4a0d49ac26a.png)
![Screenshot (70)](https://user-images.githubusercontent.com/116963622/215842278-e5b3229a-69a3-47c4-b11f-77f38e034157.png)
![Screenshot (69)](https://user-images.githubusercontent.com/116963622/215842316-06059aea-9cc4-443c-9de1-1a1cabd0ca9d.png)
## After this i took the Machine Learning approach of segmenting the customers where i choose the K-Means Clustering Algorithm for this purpose, so before feeding the data to the model i did preprocessing of the data and then fed it to the model, once the model was done clustering i assigned the clusters back to the data to get the segments of customers.
![Screenshot (72)](https://user-images.githubusercontent.com/116963622/215844090-ab8b32e5-d02e-4f8a-aa88-e9ef025258b2.png)
![Screenshot (73)](https://user-images.githubusercontent.com/116963622/215844241-dbca70d7-f313-403b-be64-20ada5a16bd2.png)
## and finally in the end i exported the data in all the ways i segmented the customers into a csv file to send it to the appropriate stakeholders.
![Screenshot (74)](https://user-images.githubusercontent.com/116963622/215845458-7584504b-0045-4e03-955f-0ba3f80540e4.png)
![Screenshot (75)](https://user-images.githubusercontent.com/116963622/215845495-a6e2bb2f-b8db-49fd-b3ee-31d91bb333b9.png)
![Screenshot (76)](https://user-images.githubusercontent.com/116963622/215845521-b27458c4-2a0d-498d-ace1-082dca750000.png)
