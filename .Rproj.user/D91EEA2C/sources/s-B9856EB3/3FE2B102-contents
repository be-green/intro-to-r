# Reading and writing data

# R expects data in tabular formats
# depending on the parser

# if you want to read csv or tab delimited files,
# my favorite is data.table::fread

if(!require(data.table)) {
  install.packages("data.table")
}

fread("data/ticker_list.csv")

# there's an analagous function called fwrite

# fwrite("data/temp.csv")

# These are both very smart parsers and ridiculously
# fast

# if you want to read an excel file, there are 
# a variety of packages that will do that.

# library(xlsx)
# library(readxl)