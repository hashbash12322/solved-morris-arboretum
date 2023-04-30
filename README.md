Download Link: https://assignmentchef.com/product/solved-morris-arboretum
<br>
Project Description:

<em>The Morris Arboretum tracks donors to their organization in Microsoft Excel. The Arboretum also uses Excel to store a list of plants in stock. As donors contribute funds to the Arboretum, they could elect to receive a plant ‘gift’ of appreciation from the Arboretum. You plan to continue gifting plants to donors as part of the Arboretum’s membership drive. The organization has grown and the files are too inefficient to handle in Excel, however, so you decide to use Microsoft Access for future Arboretum records.  In the following project, you convert Excel files into an Access database for Morris Arboretum.</em>




<strong>Instructions: </strong>

For the purpose of grading the project you are required to perform the following tasks:

<table width="678">

 <thead>

  <tr>

   <td width="72"><strong>Step</strong></td>

   <td width="517"><strong>Instructions</strong></td>

   <td width="89"><strong>Points Possible</strong></td>

  </tr>

 </thead>

 <tbody>

  <tr>

   <td width="72"><strong>1</strong></td>

   <td width="517">Start Access. Open the downloaded Access file named <em>exploring_a02_grader_h1</em>.</td>

   <td width="89">0</td>

  </tr>

  <tr>

   <td width="72"><strong>2</strong></td>

   <td width="517">Create a new table in Datasheet view using the name <strong>Donations</strong>. Switch to Design View and change <em>ID</em> to <strong>DonationID</strong>. Add the following field names to the table: <strong>DonorID</strong>, <strong>PlantID</strong>, <strong>DonationDate</strong>, and <strong>DonationAmount</strong> (in that order).</td>

   <td width="89">8</td>

  </tr>

  <tr>

   <td width="72"><strong>3</strong></td>

   <td width="517">Change the Data Type for the DonorID and PlantID fields to Number. Change the Data Type for the DonationDate field to Date/Time, and then change the Data Type for the DonationAmount field to Currency.</td>

   <td width="89">6</td>

  </tr>

  <tr>

   <td width="72"><strong>4</strong></td>

   <td width="517">View the table in Datasheet view and then add the following records to the Donations table letting Access assign the DonationID:DonorID       PlantID           DonationDate             DonationAmount<strong>24                15                   7/17/2014                  1200</strong><strong>9                  11                   8/1/2014                    1500</strong><strong>14                9                     8/15/2014                  150</strong><strong>3                  4                     9/1/2014                    1250</strong><strong>18                7                     9/2/2014                    4600</strong><strong>14               11                    9/9/2014                    450</strong></td>

   <td width="89">6</td>

  </tr>

  <tr>

   <td width="72"><strong>5</strong></td>

   <td width="517">Sort the records in the Donations table by the DonationAmount field in descending order. Save and close the table.</td>

   <td width="89">4</td>

  </tr>

  <tr>

   <td width="72"><strong>6</strong></td>

   <td width="517">Import the downloaded <em>a02_grader_h1Plants.xlsx</em> workbook as a new table in the current database. Using the wizard, specify that the first row contains column headings, set the PlantID field to be indexed with no duplicates, and set the PlantID field as the primary key. Import the table with the name <strong>Plants</strong> and do not save the import steps.</td>

   <td width="89">10</td>

  </tr>

  <tr>

   <td width="72"><strong>7</strong></td>

   <td width="517">View the Plants table in Design view and change the field size for the PlantID field to Long Integer. Save the table and the changes to the design of the table. Click Yes in the dialog box indicating that some data may be lost. Close the table.</td>

   <td width="89">4</td>

  </tr>

  <tr>

   <td width="72"><strong>8</strong></td>

   <td width="517">Begin establishing relationships in the database by adding the Donations, Donors, and Plants tables to the Relationships window. Close the Show Table dialog box. Create a one-to-many relationship between the DonorID field in the Donors table and the DonorID field in the Donations table, enforcing Referential Integrity. Select the option to cascade update the related fields.</td>

   <td width="89">10</td>

  </tr>

  <tr>

   <td width="72"><strong>9</strong></td>

   <td width="517">Create a one-to-many relationship between the PlantID field in the Plants table and the PlantID field in the Donations table. Enforce Referential Integrity. Select the option to cascade update the related fields. Save and close the Relationships window.</td>

   <td width="89">6</td>

  </tr>

  <tr>

   <td width="72"><strong>10</strong></td>

   <td width="517">Create a query using the Simple Query Wizard. From the Donations table, add the DonorID and DonationAmount fields (in that order). Ensure the query is a Detail query. Name the query <strong>Donations over 500</strong> and finish the wizard.</td>

   <td width="89">10</td>

  </tr>

  <tr>

   <td width="72"><strong>11</strong></td>

   <td width="517">View the query in Design view, and then set the criteria for the DonationAmount field so that only donations greater than <strong>500</strong> are displayed.</td>

   <td width="89">6</td>

  </tr>

  <tr>

   <td width="72"><strong>12</strong></td>

   <td width="517">Sort the query in descending order by the DonationAmount field. Save the query. Run the query and then close the query.</td>

   <td width="89">4</td>

  </tr>

  <tr>

   <td width="72"><strong>13</strong></td>

   <td width="517">Create a new query in Design view. Add the Donations, Donors, and Plants tables to the query design window. Close the Show Table dialog box. Add the DonationDate field from the Donations table, the donor’s Lastname, Firstname, and Phone fields from the Donors table (in that order).</td>

   <td width="89">8</td>

  </tr>

  <tr>

   <td width="72"><strong>14</strong></td>

   <td width="517">Add the DonationAmount field from the Donations table after the Phone field, and then add the PlantName field from the Plants table.</td>

   <td width="89">6</td>

  </tr>

  <tr>

   <td width="72"><strong>15</strong></td>

   <td width="517">Sort the query in ascending order by the date of the donation and then by the last name of the donor in ascending order. Save the query with the name <strong>Plant Pickup List</strong>, and then run the query. Close the query.</td>

   <td width="89">12</td>

  </tr>

  <tr>

   <td width="72"><strong>16</strong></td>

   <td width="517">Close all database objects. Close the database and then exit Access. Submit the database as directed.</td>

   <td width="89">0</td>

  </tr>

  <tr>

   <td width="72"></td>

   <td width="517"><strong>Total Points</strong></td>

   <td width="89"><strong>100</strong></td>

  </tr>

 </tbody>

</table>


