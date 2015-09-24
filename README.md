# R-basics
Basic in R code
# Load dataset in R

# Assign to the object:
present <-

#Load dataset
read.table("dataset_url")

# The present data frame is already loaded.

# Print the number of rows and variables with the 'dim' function:

dim(present)


# Print the names of the variables of the data frame:

names(present)


# The present dataset is already loaded.

# Find the number of boys born each year, and assign your answer to 

num_boys <- 

present$boys

# Find the number of girls born each year, and assign your answer to

num_girls <- 

present$girls

# This will print the results

num_boys

num_girls


# The present dataset is already loaded.

present

# Type here the code to create the plot:

# plot (x, y)
plot(present$year, present$girls)     #SCATTER PLOT IS CREATED BY DEFAULT#

# The present dataset is already loaded.


# Create the plot here:

plot(present$year, present$girls, type = "l")
     #THIS CREATES LINE PLOT#

#To find the documentation
?function name
#example 
?read.table

# The present dataset is already loaded.

# The vector babies:

babies <- 
present$boys + present$girls


# Your plot

plot(present$year, babies, type = "l")
  

# Load the cdc data frame into the workspace:
load(url("http://assets.datacamp.com/course/dasi/cdc.Rdata"))
