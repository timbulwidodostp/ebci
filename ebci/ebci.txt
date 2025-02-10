# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Robust empirical Bayes confidence intervals Use ebci With (In) R Software
install.packages("ebci")
library("ebci")
ebci = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ebci/main/ebci/ebci.csv",sep = ";")
# Estimation Robust empirical Bayes confidence intervals Use ebci With (In) R Software
ebci <- ebci(theta25 ~ stayer25, data=ebci, se=se25, weights=1/se25^2)
ebci$delta
ebci$mu2
ebci$kappa
# Robust empirical Bayes confidence intervals Use ebci With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished