# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Bootstrap test for slope homogeneity in large panels Use xtbhst With (In) R Software
install.packages("xtbhst")
library("xtbhst")
# Estimation Bootstrap test for slope homogeneity in large panels Use xtbhst With (In) R Software
xtbhst_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/xtbhst_r/main/xtbhst_r/xtbhst_r.csv",sep = ";")
xtbhst <- xtbhst(xtbhst ~ xtbhst_, data = xtbhst_r, id = "id", time = "time", reps = 999, seed = 123456)
xtbhst
# Bootstrap test for slope homogeneity in large panels Use xtbhst With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished