# Hello
 

## Lucy Mutuota, Alx-Pre_course


````
pip install me
````




## Usage


````python
import csv

with open("sample.csv","r") as csvinput: # read input csv file
    reader = csv.reader(csvinput) # create a reader
    for row in reader:
        print(row[0])
````