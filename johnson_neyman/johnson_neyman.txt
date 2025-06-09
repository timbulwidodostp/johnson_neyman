# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Calculate Johnson-Neyman intervals for 2-way interactions Use johnson_neyman (interactions) With (In) R Software
install.packages("interactions")
library("interactions")
johnson_neyman = read.csv("https://raw.githubusercontent.com/timbulwidodostp/johnson_neyman/main/johnson_neyman/johnson_neyman.csv",sep = ";")
# Estimation Calculate Johnson-Neyman intervals for 2-way interactions Use johnson_neyman (interactions) With (In) R Software
fit <- lm(Income ~ HSGrad + Murder*Illiteracy, data = johnson_neyman)
johnson_neyman <- johnson_neyman(model = fit, pred = Murder, modx = Illiteracy)
johnson_neyman
# Calculate Johnson-Neyman intervals for 2-way interactions Use johnson_neyman (interactions) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished