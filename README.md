# Amazon_Vine_Analysis
Perform analysis on Amazon Data sets using Pyspark, ETL, AWS RDS, AWS S3 bucket, and pgAdmin. 
## Overview of the analysis 
For this analysis of the project is to choose one of the datasets to anlysis. All datasets are stored in the cloud services which is storage containing large amounts of data in a remote location. This project to anlyze the Automotive dataset. Use Pyspark to perform ETL to extract the dataset, transform the data, connect to AWS RDS. Then load transformed data into pgAdmin to determin if any bias toward favorable reviews members in the dataset. 
## Result:
- Total Review Paid count 82

![Screenshot 2022-12-26 at 12 42 31](https://user-images.githubusercontent.com/112133209/209582288-d1db94e3-2c28-4c4d-a490-69d2921d892f.png)

- Total Review Unpaid count 24742

![Screenshot 2022-12-26 at 12 42 35](https://user-images.githubusercontent.com/112133209/209582327-12a3d016-921d-46aa-8029-ce85318f4e15.png)

- Total # of 5 star review paid 33

![Screenshot 2022-12-26 at 12 45 18](https://user-images.githubusercontent.com/112133209/209582389-c6f31a7e-b905-460f-807c-4a3a6607bbfa.png)

- Total # of 5 star review Unpaid 12807

![Screenshot 2022-12-26 at 12 45 22](https://user-images.githubusercontent.com/112133209/209582395-0b46c97e-c9da-40e9-a4c3-8a81753ce315.png)

- Percentage of 5 star reviews paid 40.243902%

![Screenshot 2022-12-26 at 12 42 50](https://user-images.githubusercontent.com/112133209/209582348-42972c92-8dd4-4109-87d6-f6dd5b51af17.png)

- Percentage of 5 star reviews unpaid 51.762186%

![Screenshot 2022-12-26 at 12 42 56](https://user-images.githubusercontent.com/112133209/209582360-2b316be8-cca8-4423-a959-232fb1304dfe.png)

## Summary
After extracting dataset from Amazon to pgAdmin then to vine analysis. Based on the Amazon review data, there seems to be majority of unpaid count by 24742 more then paid reviewers. Paid reviewer count is 82. As a result we can say that there were about 52% five star unpaid contributed reviews while about 40% of paid contributed to the automotive reviews. Extracting the same Vine/non-Vine review data from numerous other products (such as groceries, sports, shoes, electronics, etc.) on Amazon to reveal the non-bias in other product categories is one additional analysis that could be carried out with the dataset to support the findings of the current analysis. 
## Additional notes
Importing datasets into AWS S3 bucket seems to take time to upload. Then the writing dataset into pgAdmin tables took a while. 
