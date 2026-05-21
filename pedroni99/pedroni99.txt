# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Panel cointegration tests - bivatiate case Use pedroni99 (pco) With (In) R Software
install.packages("pco", repos="http://R-Forge.R-project.org")
library("pco")
# Estimate Panel cointegration tests - bivatiate case Use pedroni99 (pco) With (In) R Software
pedroni99 = read.csv("https://raw.githubusercontent.com/timbulwidodostp/pedroni99/main/pedroni99/pedroni99.csv",sep = ";")
pedroni99_ = read.csv("https://raw.githubusercontent.com/timbulwidodostp/pedroni99/main/pedroni99/pedroni99_.csv",sep = ";")
pedroni99 <- pedroni99(pedroni99, pedroni99_)
pedroni99
# Panel cointegration tests - bivatiate case Use pedroni99 (pco) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished