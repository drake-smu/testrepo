#  Data science profile
```
###############
# 4. - Data Profile
###############
categories <- c("Computer\nProgramming", "Math", "Statistics", "Machine\nLearning", "Domain\nExpertise", "Communication and \nPresentation Skills", "Data\nVisualization");
ranks <- c(4,5,3,3,4,2,3);

tim <- data.frame(category=categories,rank=ranks, stringsAsFactors = FALSE);

barplot(tim$rank,names.arg =tim$category, cex.names=0.7,main = "Data Science\nProfile");

write.table(tim,file="dunken");
```
