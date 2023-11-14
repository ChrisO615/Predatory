# Predatory
nematode <- read.csv("nematode.csv")

Predatory <- nematode$Predatory

Site <- nematode$Site

plot(nematode$Predatory, 
     breaks = 15,
     col = "purple", 
     xlab = "Site",
     ylab = "Frequency",
     main = "Predatory Nematodes per Site")
