
# Assignment 1
This project was made in collaboration with Angela Gomez Sacristan, Mariam El Akal Chaji and Marta Fernandez Gonzalez.

It consists in two main task using Object- oriented programming: 
1. Simulate planting 7 grams of seed from each of the records in the seed stock genebank.
   Then you should update the genebank information to show the new quantity of seeds that remain after planting. 
   The new state of the genebank should be printed to a new file, using exactly the same format as the original file seed_stock_data.tsv. 
   If the amount of seed is 0 or less than 0 a message should appear on the screen. 
   
2. Process the information in cross_data.tsv and determine which genes are genetically linked. To achieve this, you will have to do a Chi-square test on the F2 data. 
   If you discover genes that are linked, this information should be added as a property of each of the genes (they are both linked to each other). 
   
To run the script use ruby process_database.rb ./Data/gene_information.tsv ./Data/seed_stock_data.tsv ./Data/cross_data.tsv

# Bibliography

We have used the following bibliography in order to check out for some ideas for our assignment's code: 

> How to use the initialize method in ruby. RubyGuides. (2019, July 23). Retrieved November 3, 2022, from https://www.rubyguides.com/2019/01/ruby-initialize-method/ 

> Contents. Reading from a CSV File | Ruby for Beginners. (n.d.). Retrieved November 3, 2022, from http://ruby-for-beginners.rubymonstas.org/exercises/mailbox_csv.html 

> Ruby array methods: Complete guide to top 13 methods in ruby array. EDUCBA. (2021, March 3). Retrieved November 3, 2022, from https://www.educba.com/ruby-array-methods/ 

> Ruby: Loops (for, while, do..while, until). GeeksforGeeks. (2021, July 5). Retrieved November 3, 2022, from https://www.geeksforgeeks.org/ruby-loops-for-while-do-while-until/#forLoop 

> Otieno, J. (1969, January 1). If conditions in ruby. Retrieved November 3, 2022, from https://linuxhint.com/if-conditions-in-ruby/#:~:text=Ruby%20If%20Statements%20The%20if%20statement%20takes%20a,or%20false.%20If%20true%2C%20it%20performs%20a%20decision. 

> Ruby: Datetime now() function. GeeksforGeeks. (2020, January 9). Retrieved November 3, 2022, from https://www.geeksforgeeks.org/ruby-datetime-now-function/ 

> Rails datetime.now without time. Stack Overflow. Retrieved November 3, 2022, from https://stackoverflow.com/questions/8196434/rails-datetime-now-without-time 

> Can I delete columns from CSV using ruby? Stack Overflow. Retrieved November 5, 2022, from https://stackoverflow.com/questions/9184504/can-i-delete-columns-from-csv-using-ruby 
