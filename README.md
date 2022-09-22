# Analysis_sales_DataWarehouse_SSAS
A demonstration for using SSAS in analyzing a Data warehouse "sales" with "MDX" answered questions.

USED frameworks:
-Sql server management studio 2017
-Visual studio 2017
-Datatools for visual studio 2017(SSIS, SSAS and SSRS)

Steps of Implementation:
1) Import "Sales" DW into your SSMS.
2)Create a new solution in visual studio with type Business Intelligence --> Analysis services --> Analysis services multidimentions and data mining models.
3)Identify your data source(make a new connection with "sales" DW).
4)Identify the data source views and attach your admin credential.
5)prepare the cube with all the possible dimensions measure and identify the fact table. 
6)Think about all the calculations, KPIs, translation, perspectives and user-added measures you want to add.
finally process your Cube and have fun!

To run MDX queries 
--Login to SSMS with server type:analysis services 
--Identify the DW "sales" you will work on a
--Identify the cube you will work on which is "sales_Q3" cube.
