library(tidyverse) # loading the package
renv::snapshot()  # save the state of the library

data("iris") # loading 'iris' data
summary(iris)
str(iris)

ggplot(data=iris, aes(x = Sepal.Length, y = Sepal.Width))+
  geom_point(aes(color=Species, shape=Species)) +
  xlab("Sepal Length") +
  ylab("Sepal Width") +
  ggtitle("Sepal Length-Width")

box <- ggplot(data=iris, aes(x=Species, y=Sepal.Length))

box + 
  geom_boxplot(aes(fill=Species)) +
  ylab("Sepal Length") +
  ggtitle("Iris Boxplot") +
  stat_summary(fun.y=mean, geom="point", shape=5, size=4)

