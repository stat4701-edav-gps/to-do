#To Do
To Do list for everyone

#Group tasks:
* (RC, EB) Formulate questions for Prof. about analytical methods (regression vs. other methods).
* (SG) Work on SQL queries for random selections (contingent on either database or SQL/csv wrapper). 
* (All or someone could volunteer to take lead getting started) Start the Presentation outline (https://github.com/stat4701-edav-gps/presentation) - can be edited inline via GitHub website. Edit README.md file.  
* (All or someone could volunteer to take lead on scheduling) Figure out which day/time/place for weekend of April 25-26. 
* Perhaps we should include some kind of interactive component to the project - discuss at next meeting
 * Good idea!

These Other Group tasks will likely need to be broken out in to smaller steps for individual members. 

#Individual tasks

##Richie
* Create map that combines distance from roadbed and block height
* Create that map within Crosslet to show the outliers
* Look into some more statistics, especially with k-means on the heights to see if we can improve the regression
* Create the slides

##Emilie
* Write out actual research questions 
 * Could we use [this text from your taxi-analysis repo?](https://github.com/stat4701-edav-gps/taxi-analysis) 
* Put together analysis plan for larger feedback with **Richie**.
* Draft a list of questions for review with more spatial stats inclined folks.
* Recode and create any new vars
* Complete the basic exploratory work,
* and check assumptions etc. for model fitting.
* Look into big vis package - might be interesting

##Danny

* Create 3D version of distributed building height for census block, like the buffer one but with block. 
* Create a percent block covered with building footprint. 

* Study sample
 * Determine Census Block size range for SQL statement.
 * Update that SQL code for [BigQuery R code.](https://github.com/stat4701-edav-gps/bigrquery/blob/master/BigQuery.R)
 * Consider minimum counts of buildings and maybe count of pickups/dropoffs

* <s>New vars:</s>
 * <s>Create Census Block flag variable for Park or No Park.</s> didn't do, will be a lot more work. Using Block size and count buildings will help for this. 
 * <s>Create Census Block flag variable for Buildings or No Buildings.</s>
 * <s>Create Census Block Size variable.</s>
 * <s> Maybes 
    * Maybe also measure of possible maximum distance across block, 
    * or measure of block compactness </s>
 * <s>Create descriptive roabded stats (pandas) file.</s>
 * <s>Merge descriptive describe() stats to Master data file</s> Uploaded to Google [BigQuery for R code here](https://github.com/stat4701-edav-gps/bigrquery/blob/master/BigQuery.R). 

* <s>New Maps:</s>
 * <s>Create Median Distance to Roadbed groupby dataset.</s>
   * <s>map Median Distance</s>

* Database:
 * <s>Coordinate with Amazon about possible Free account, setup PostgreSQL (SQLite or equiv. ) database.</s>
 * <s>Work with **Sankara** to get SQL queries to pull data out of database for analysts.</s> 
 * <s>Alternatively is this doesn’t work we can look into https://code.google.com/p/gcsvsql/</s>
 * Posted some [BigQuery for R code here](https://github.com/stat4701-edav-gps/bigrquery/blob/master/BigQuery.R)
 
##Sankara
