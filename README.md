# Time-Series-Average-Line
# For use inside spotfire
# Very simple data table creation but capturing for later use
# For TERR

prod <- production
Avg1 <- aggregrate(prod[,4:10], by=list(prod$TotalProdMonths), FUN=mean, na.rm=TRUE)


#Screenshots from Spotfire
#![image](https://user-images.githubusercontent.com/53614800/201724865-a38f992b-b09c-4400-b714-1805079d79dd.png)
#![image](https://user-images.githubusercontent.com/53614800/201724898-a578188e-1197-4d97-85a0-956013ca9af2.png)
#![image](https://user-images.githubusercontent.com/53614800/201724936-0f217d9e-71cb-4a79-99a8-97584ff1490e.png)
#![image](https://user-images.githubusercontent.com/53614800/201725000-1a8fbcef-e226-4675-8b88-7b2f968f0a9d.png)
