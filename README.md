# This project is part of the Bertelsmann Tech Scholarship Challenge Course - Introduction to Problem Solving with Advanced Analytics Nanodegree Program.

Project Overview

In this project, you will analyze a business problem in the mail-order catalog business. You're tasked with predicting how much money your company can expect to earn from sending out a catalog to new customers. This task will involve building the model and applying the results in order to provide a recommendation to management.

You’ve been asked to predict the expected profit from these 250 new customers. Management does not want to send the catalog out to these new customers unless the expected profit contribution exceeds $10,000.

The costs of printing and distributing is $6.50 per catalog.
250 catalog in total
cost for printing all the catalog is 6.5 * 250 

The average gross margin (price - cost) on all products sold through the catalog is 50%.

Make sure to multiply your revenue by the gross margin first before you subtract out the $6.50 cost when calculating your profit.

Score_No: The probability that the customer WILL NOT respond to the catalog and not make a purchase.

Score_Yes: The probability that the customer WILL respond to the catalog and make a purchase.

Hint: We want to calculate the expected revenue from these 250 people in order to get expected profit. This means we need to multiply the probability that a person will buy our catalog as well. For example, if a customer were to buy from us, we predict this customer will buy $450 worth of products. At a 30% chance that this person will actually buy from us, we can expect revenue to be $450 x 30% = $135.

**Project Overview.txt** contains necessary information on the business problem. \
**p1-customers.xlsx** & **p1-mailinglist.xlsx** are the datasets. \
**Predicting Catalog Demand.ipynb** is the jupyter notebook containing the solution to the identified business problem. \
**Predicting Catalog Demand.yxmd** is a workflow file, in it is the solution to the problem posed. File can be opened using Alteryx Designer. 
