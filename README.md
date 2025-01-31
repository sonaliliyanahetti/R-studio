# R-studio

#R is independent open source implementation similar to S
#for R ---> R studio,Rattle we use R studio

print(100:150)

#current working directory
getwd()

#change current working directory
setwd("C:\\Users\\User\\Desktop\\R")
#or ("C:/Users/User/Desktop/R")

getwd()

#help
?solve
help("data.frame")

#install packages
install.packages("ggplot2")
#if not you can change it using packages and tick on wanted package

#scalar operation
2+4
3-2
4/2
2*4
2^3
400%%2
401%%2

#logical operator

x=3
y=-4
isTRUE(x==y)
isTRUE(x>y)
isTRUE(x<y)
isTRUE(x<=y)
isTRUE(x==6)
isTRUE(x<6& y>0)
isTRUE(x<6|y>0)
isTRUE(x!=y)

#Assignment operators

#local environmet
a=4
a<-5

#global environmet
a<<-5 # used in functions


#Fundamental data objects

#vector - a sequence of numbers or characters, or higher-dimensional arrays like matrices.   
#list - a collection of objects that may themselves be complicated.   
#factor - a sequence assigning a category to each index.   
#data.frame - a table-like structure (experimental results often collected in this form).   
#environment - hash table. A collection of key-value pairs.  

#vector w=object,c=defining vector
w<-c(1,2,3,4,5)
w
class(w)

e<-c("a","b","c")
e
class(e)

#factor
gender<-c(0,1,0,1,1,0,1,0)
gender
Gender<-factor(gender,c(0,1),c("Male","Female"))
Gender
class(Gender)


#list
p<-c(1,2,3)#vector
q<-"green"#character variable
r<-21 #numerical variable
p
r
q

Data<-list(p,q,r)
Data

#matrix
m1<-matrix(c(1,2,3,4),nrow = 2,ncol = 2, byrow = TRUE)
#byrow means the filling method if it is filled by row by row this is true
m1
class(m1)

#dataframe

