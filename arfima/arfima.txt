# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit a fractionally differenced ARFIMA model Use arfima (forecast) With (In) R Software
install.packages("forecast")
library("forecast")
library("fracdiff")
arfima = read.csv("https://raw.githubusercontent.com/timbulwidodostp/arfima/main/arfima/arfima.csv",sep = ";")
# Estimation Fit a fractionally differenced ARFIMA model Use arfima (forecast) With (In) R Software
arfima <- arfima$arfima
arfima <- arfima(arfima)
summary(arfima)
tsdisplay(residuals(arfima))
# Fit a fractionally differenced ARFIMA model Use arfima (forecast) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished