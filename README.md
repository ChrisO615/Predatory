# Predatory
nematode <- read.csv("nematode.csv")

Predatory <- nematode$Predatory

boxplot(list(Group1 = Predatory), 
        main = "Predatory Boxplot", 
        ylab = "Number of Individuals")
