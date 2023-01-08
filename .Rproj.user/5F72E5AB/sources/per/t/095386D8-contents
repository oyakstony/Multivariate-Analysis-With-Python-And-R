data <- read.csv('HR_comma_sep.csv')

data


data_standardize <- as.data.frame(scale(data[1:5]))
data_standardize



data.mat <- as.matrix(data_standardize)
cov.mat <- cor(data_standardize)


pca <- prcomp(data_standardize,center = T,scale. = T)
summary(pca)


