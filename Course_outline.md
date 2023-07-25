### Course Outline

Week 1: Introduction to biological research questions and real-world datasets.  
Entering data and quick stats/visualiation - revison of first year, then more detail on data downloading, reading in different file types and formatting
    pd.read_csv, pd.read_table, pd.read_excel
    df.set_index
    df.info
    df.sort_values
    df.dropna
    df.T
    df.drop
    df.iloc
    df.reset_index
    df.apply(pd.to_numeric)
    df.to_csv, df.to_excel, df.to_pickle



Week 2: Tidy data. Re-arranging and manipulating data. Lamba, applying functions
    df["COLUMN_NAME"] = [LIST]
    df.drop(columns=["Goats"])
    df.sort()
    df["Logged_oats"] = np.log(df["Oats")
    df = df.assign(Profit=lambda x: (x['Sheep'] *10 +  x['Barley'] *5 +  x['Oats']*3))
    df[df["Soil"]=="Clay"]
    df[df["Sheep"] > 10]
    df[df["Soil"].isin(["Loam", "Sand"])]
    df.groupby("Soil")["Field"].count()
    df.reset_index
  

Week 3: Data visualisation  
How to choose appropriate visualisations for different data types.  Coding for producing a range of plot types, for data exploration.  

Week 4: Introduction to the flavour datasets, hypothesis development and testing
session where student groups are able to discuss with staff in charge of each dataset outcomes of their investigations.  Including a presentation from the “dataset coordinator” about the data and the advanced or wider implications/applications of the datasets 

Week 5: Combining data, Filtering data, slicing and dicing, indexes
Different types of joins.  First workshop working with the chosen data set
pd.concat()
pd.merge()
pd.join()
Filtering
grouping
summarising



Week 6: Break.

Week 7: Revision of inferential stats from first year and building on this
Principals of testing variation between groups.  Coding to run bootstrapping tests. Describing commonly used approaches (t-tests).  

Week 8: Multivariate analysis 1.  
Introduction to the concepts of multivariate statistics.  Clustering

Week 9: Multivariate analysis 2.   
PCA analysis

Week 10: Principles of data presentation  
Coding and principles for communicating data
ppt on making a good poster
Workshop 1 working on flavour data
Workshop 2 producing a poster

Week 11: Class test and Poster day  
Class test in first session - Data analysis problem to be completed in 40 minutes.  Cleaning, joining datasets, generating a graph to answer a question.
Friday class - An event for students to display and present their posters, for assessment by staff and peers.  Will be accompanied by food and drinks at Murchiston house.  Mix of electronic pasters and printed  

Coffee, tea, cakes for 200.


### Assessment  
Weekly quizzes at beginning of each class (total 20%)  Expect HIGH - is measuring attendance as well
Portfolio (15%)  Expect HIGH most got >70 in first year.  up to 40% will get the full 15%
Class test  (25%)  Expect LOW
Poster 40% (assessed by staff (30%) and peers (10%))   Expect HIGH (Peer weightling?)

Missing Portfolio is a force fail.  Otherwise need 40% total to pass course
Doable with a good poster group and portfolio

### Delivery  
Recorded lectures (from course face) to introduce topics  
Workshop (1 demonstrator:15 students) to work through detailed notebook exploring the topic  

### Resources  
Largest Nucleus lecture theatre, flexible seating for workshops  
BTO support familiar with notebooks  