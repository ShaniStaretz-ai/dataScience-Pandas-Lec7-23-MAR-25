# dataScience-Pandas-Lec7-2n3-MAR-25
Pandas - continue
* iat[row_index,col_index]= access/set single value by indexes, like cell[row_i][col_i]
* at[row_label,col_label]= access/set single value by labels. 
  * if there are more the one values will return all
  * df_hw_mobile.at['LA','Account length'] = df_hw_mobile.loc['LA']['Account length']
  ![img.png](img.png)
* set_index(label): the values must be uniques. 
* df.is_unique= attribute - return false if the values is not unique
* df.values_counts()= return the count for each value
* duplicated()= return the duplicate row
* len(df)/len(df[label])= length total values/length of values in given label
* 