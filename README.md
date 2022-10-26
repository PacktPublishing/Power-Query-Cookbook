# Power Query Cookbook

<a href="https://www.packtpub.com/product/power-query-cookbook/9781800569485"><img src="https://static.packt-cdn.com/products/9781800569485/cover/smaller" alt="Power Query Cookbook" height="256px" align="right"></a>

This is the code repository for [Power Query Cookbook](https://www.packtpub.com/product/power-query-cookbook/9781800569485), published by Packt.

**Use effective and powerful queries in Power BI Desktop and Dataflows to prepare and transform your data**

## What is this book about?

Power Query is a data preparation tool that enables data engineers and business users to connect, reshape, enrich, and transform their data to facilitate relevant business insights and analysis. With Power Query's wide range of features, you can perform no-code transformations and complex M code functions at the same time to get the most out of your data.

This Power Query book will help you to connect to data sources, achieve intuitive transformations, and get to grips with preparation practices. Starting with a general overview of Power Query and what it can do, the book advances to cover more complex topics such as M code and performance optimization. You'll learn how to extend these capabilities by gradually stepping away from the Power Query GUI and into the M programming language. Additionally, the book also shows you how to use Power Query Online within Power BI Dataflows.

By the end of the book, you'll be able to leverage your source data, understand your data better, and enrich it with a full stack of no-code and custom features that you'll learn to design by yourself for your business requirements.

This book covers the following exciting features: 
* Understand how to use Power Query to connect and explore data
* Explore ways to reshape and enrich data
* Discover the potential of Power Query across the Microsoft platform
* Build complex and custom transformations
* Use M code to write new queries against data sources
* Use the Power Query Online tool within Power BI Dataflows
* Implement best practices such as reusing dataflows, optimizing expanding table operations, and field mapping

If you feel this book is for you, get your [copy](https://www.amazon.in/Power-Query-Cookbook-effective-Dataflows-ebook/dp/B098BLQW9X/ref=sr_1_2?dchild=1&keywords=power+query+cookbook&qid=1631519435&sr=8-2) today!

<a href="https://www.packtpub.com/product/power-query-cookbook/9781800569485"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
(OldSalesAmount as number, Discount as number, TotalCosts as number) =>
let 
 NetSales = OldSalesAmount - (OldSalesAmount * Discount ) - TotalCosts 
in
 NetSales
 
```
**Following is what you need for this book:**
This book is for data analysts, BI developers, data engineers, and anyone looking for a desk reference guide to learn how Power Query can be used with different Microsoft products to handle data of varying complexity. Beginner-level knowledge of Power BI and the M Language will help you to get the best out of this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-10).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  	1-10	   |   	Power BI Desktop and Power BI Gateway                                			  | Windows(Any) | 		

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781800569485_ColorImages.pdf).

### Related products <Other books you may enjoy>
* Learn Power BI  [[Packt]](https://www.packtpub.com/free-ebook/learn-power-bi/9781838644482) [[Amazon]](https://www.amazon.in/Learn-Power-developing-interactive-intelligence-ebook/dp/B07X32RJDB/ref=sr_1_2?dchild=1&keywords=Learn+Power+BI&qid=1631520425&sr=8-2)
  
* Expert Data Modeling with Power BI  [[Packt]](https://www.packtpub.com/product/expert-data-modeling-with-power-bi/9781800205697) [[Amazon]](https://www.amazon.in/Expert-Data-Modeling-Power-optimized/dp/1800205694/ref=sr_1_1?dchild=1&keywords=Expert+Data+Modeling+with+Power+BI&qid=1631520397&sr=8-1)
  
  
  
## Get to Know the Author
**Andrea Janicijevic** is a cloud solution architect and works in the world of analytics and business intelligence, constantly expanding her knowledge in the field of data. From the outset, she has been working on analytics platforms, helping clients to better adopt cloud technology across a wide range of industries and company sizes.
She studied economics and management of innovation and technology at Bocconi University in Milan and during her studies, she started working at Microsoft in 2018.
She began working with the Microsoft analytics platform, including Power BI, becoming a trusted technical advisor for business and technical users. She later started collaborating with Packt, accepting the challenge of sharing her experience with Power Query.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781800569485">https://packt.link/free-ebook/9781800569485 </a> </p>