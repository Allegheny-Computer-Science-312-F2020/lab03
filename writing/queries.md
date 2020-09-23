
# Name:
TODO

# Date:
TODO


Please respond to the lab assignment sheet's questions-in-blue below.



1. In your own words, write the questions that the following queries answer;

 - select count(sa.protID) from nprot n, sars sa where sa.protID == n.protID;

 - select count(distinct(sa.protID)) from nprot n, sars sa, mprot m where sa.protID ==
n.protID AND sa.protID == m.protID;


2. Please give an obvious reason why the two queries below have the same output.

 - select count(distinct(s.protID)) from sars s;

 - select count(s.protID) from sars s;


3. Write the query to list all distinct Organisms which are common to both the sars and nprot
tables.


4. Write the query to count all distinct Organisms which are common to all tables: sars, nprot,
mprot and sprot.


5. How many distinct protIDs are there in the sars where the organism == "Mus musculus (Mouse)"?


6. What is the average length of the proteins in the sars table for the organism "Mus musculus (Mouse)"


7. What is the largest length of the proteins in the sprot table for the organism "Mus musculus (Mouse)"


8. List the protIDs and their associated organisms from the sars table where the length of the
protein is equal to 240.


9. List the protIDs and their associated organisms from the nprot table where the length of the
protein is equal to 220.


10. Running queries can help you find patterns that you may not expect to find. What natural
trend(s) did you notice from the result of your two previous queries above?


11. Write a question of your own that uses all four tables to answer, then provide the query to
respond to your question involving all four tables.




#Note:
Did you remember to add your name at the top of this document?
