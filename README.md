Download Link: https://assignmentchef.com/product/solved-itse2321-program-10-household-records
<br>
The results of a survey of the households in your township are available for public scrutiny.  Each record contains data for one household, including a four-digit integer identification number, the annual income for the household, and the number of household members.  Write a program to read the survey results into an ArrayList and perform the following analysis.

<ol>

 <li>Print the record of each household included in the survey in a three-column format with headings.</li>

 <li>Calculate and print the average household income.</li>

 <li>List the identification number and income of each household that exceeds the average.</li>

 <li>Determine and print the identification number and income of households that have income below the 2019 United States’ Contiguous States poverty level.</li>

 <li>Determine and print the percentage of households that have income below the 2019 United States’ Contiguous States poverty level.</li>

</ol>

<strong>Compute the poverty level income using the formula below</strong>.




<h1>                    povertyLevel = 16910.00 + 4420.00 * (m – 2)</h1>

<em> </em>

where <strong><em>m</em></strong> is the number of members of each household.  This formula shows that the poverty level depends on the number of family members, <strong><em>m</em></strong>, and the poverty level income increases as <strong><em>m</em></strong> gets larger.




The input data is available in a file named, <strong><em>Program10.txt</em></strong>, on the I: drive and has the format of identification number, annual income for the household, and the number of household members.




Define a Class named, <strong>HouseHold</strong>, that contains the attributes described earlier.  Write a test Class named, <strong>TestHouseHold</strong>, that creates an ArrayList of <strong>HouseHold</strong> objects