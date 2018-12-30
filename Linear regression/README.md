# Get familiar with pandas

* Read file: data  = pd.read_csv()   

* Read dimension:  data.shape

* Insert column: data.insert()   
e.g.,  inserting column with static value in data frame. data.insert(2, "Team", "Any") 

* Extract rows or columns: 
RECAP: three methods

  * loc gets rows (or columns) with particular labels from the index.

  * iloc gets rows (or columns) at particular positions in the index (so it only takes integers).

  * ix usually tries to behave like loc but falls back to behaving like iloc if a label is not present in the index.

  * Summary: iloc.[] works based on integer positioning. So no matter what your row labels are, you can always.   
  e.g., get the first row by doing .iloc[0] or the last five rows by doing .iloc[-5:]


# Get familiar with numpy

* np.power

* 1D matirx element extraction   
e.g.,theta = np.matrix([0, 0]), theta[0, 1]

# More abuot Pandas Framework   

* Pandas is a popular Python package for data science, and with good reason: it offers powerful, expressive and flexible data structures that make data manipulation and analysis easy, among many other things. The DataFrame is one of these structures.

* Data frame as a way to store data in rectangular grids that can easily be overviewed. 

* In general, you could say that the Pandas DataFrame consists of three main components: the data, the index, and the columns.

* Resources: https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python

