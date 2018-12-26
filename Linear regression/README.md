# Get familiar with pandas
* Read file: data  = pd.read_csv
* Read dimension:  data.shape
* Insert column: .insert() e.g.,  inserting column with static value in data frame. data.insert(2, "Team", "Any") 
* Extract rows or columns: 
iloc.[] works based on integer positioning. So no matter what your row labels are, you can always, e.g., get the first row by doing .iloc[0]
or the last five rows by doing .iloc[-5:]
RECAP: three methods
loc gets rows (or columns) with particular labels from the index.
iloc gets rows (or columns) at particular positions in the index (so it only takes integers).
ix usually tries to behave like loc but falls back to behaving like iloc if a label is not present in the index.
# Get familiar with numpy
* np.power
