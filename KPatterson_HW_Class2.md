### Homework for CLASS 2
Kim Patterson 
**Homework for CLASS 2**

1. Using `chipotle.tsv` in the `data` subdirectory:
    
	i. Look at the head and the tail, and think for a minute about how the data is structured. What do you think each column means? What do you think each row means? Tell me! (If you're unsure, look at more of the file contents.)
	**ANSWER :** *Column 1: order id, Column 2: quantity, Column 3: item name, Column 4: Choice description, Column 5: Price*
    
	ii. How many orders do there appear to be?
	**ANSWER :** *1,834*
    
	iii. How many lines are in the file?
	**ANSWER :** *4,623*
    
	iv. Which burrito is more popular, steak or chicken?
	**ANSWER :** *4,623*
    
	v. Do chicken burritos more often have black beans or pinto beans?
	**ANSWER :** *Chicken  – pipe command used to count(grep|wc-l)*

2. Make a list of all of the CSV or TSV files in the DAT7 repo (using a single command). Think about how wildcard characters can help you with this task.
   **ANSWER :** *In “data” directory – line command: "find *.csv" OR "find *.tsv"*

3. Count the number of occurrences of the word 'dictionary' (regardless of case) across all files in the DAT7 repo.
   **ANSWER :** *16 (grep –r –i . | wc –l)*

4. **Optional:** Use the the command line to discover something "interesting" about the Chipotle data. The advanced commands below may be helpful to you!
   **ANSWER :** *59 duplicate or “non unique” orders (sort file pass to new file, then uniq –c | wc –l results in 4564. Original file line count was 4623)*

