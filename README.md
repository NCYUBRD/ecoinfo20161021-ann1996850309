# ecoinfo20161021-ann1996850309
ecoinfo20161021-ann1996850309 created by GitHub Classroom
#森三甲1032149柯品安
library(data.table)
setwd("C:/Users/user1/Desktop/-_1032149_--master/-_1032149_--master/1032149")
#設定檔案資料夾
txtpath = "C:/Users/user1/Desktop/raw/"
#檔案list
txtfilesn = list.files( path = txtpath, pattern=".txt" )
txtfilesn
#資料匯入
rttxt = paste(txtpath,txtfilesn)
rttxt
col_names = c('stno','yyyymmddhh','PS01','TX01','RH01','WD01','WD02','PP01','SS01')
col_classes = c('character', 'integer', 'float', 'float', 'integer', 'float','integer', 'float','float')
rawdata200601<- data.table::fread("C:/Users/user1/Desktop/raw/200601_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200602<- data.table::fread("C:/Users/user1/Desktop/raw/200602_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200603<- data.table::fread("C:/Users/user1/Desktop/raw/200603_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200604<- data.table::fread("C:/Users/user1/Desktop/raw/200604_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200605<- data.table::fread("C:/Users/user1/Desktop/raw/200605_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200606<- data.table::fread("C:/Users/user1/Desktop/raw/200606_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200607<- data.table::fread("C:/Users/user1/Desktop/raw/200607_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200608<- data.table::fread("C:/Users/user1/Desktop/raw/200608_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200609<- data.table::fread("C:/Users/user1/Desktop/raw/200609_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200610<- data.table::fread("C:/Users/user1/Desktop/raw/200610_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200611<- data.table::fread("C:/Users/user1/Desktop/raw/200611_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200612<- data.table::fread("C:/Users/user1/Desktop/raw/200612_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200701<- data.table::fread("C:/Users/user1/Desktop/raw/200701_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200702<- data.table::fread("C:/Users/user1/Desktop/raw/200702_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200703<- data.table::fread("C:/Users/user1/Desktop/raw/200703_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200704<- data.table::fread("C:/Users/user1/Desktop/raw/200704_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200705<- data.table::fread("C:/Users/user1/Desktop/raw/200705_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200706<- data.table::fread("C:/Users/user1/Desktop/raw/200706_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200707<- data.table::fread("C:/Users/user1/Desktop/raw/200707_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200708<- data.table::fread("C:/Users/user1/Desktop/raw/200708_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200709<- data.table::fread("C:/Users/user1/Desktop/raw/200709_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200710<- data.table::fread("C:/Users/user1/Desktop/raw/200710_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200711<- data.table::fread("C:/Users/user1/Desktop/raw/200711_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200712<- data.table::fread("C:/Users/user1/Desktop/raw/200712_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200801<- data.table::fread("C:/Users/user1/Desktop/raw/200801_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200802<- data.table::fread("C:/Users/user1/Desktop/raw/200802_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200803<- data.table::fread("C:/Users/user1/Desktop/raw/200803_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200804<- data.table::fread("C:/Users/user1/Desktop/raw/200804_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200805<- data.table::fread("C:/Users/user1/Desktop/raw/200805_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200806<- data.table::fread("C:/Users/user1/Desktop/raw/200806_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200807<- data.table::fread("C:/Users/user1/Desktop/raw/200807_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200808<- data.table::fread("C:/Users/user1/Desktop/raw/200808_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200809<- data.table::fread("C:/Users/user1/Desktop/raw/200809_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200810<- data.table::fread("C:/Users/user1/Desktop/raw/200810_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200811<- data.table::fread("C:/Users/user1/Desktop/raw/200811_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200812<- data.table::fread("C:/Users/user1/Desktop/raw/200812_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200901<- data.table::fread("C:/Users/user1/Desktop/raw/200901_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200902<- data.table::fread("C:/Users/user1/Desktop/raw/200902_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200903<- data.table::fread("C:/Users/user1/Desktop/raw/200903_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200904<- data.table::fread("C:/Users/user1/Desktop/raw/200904_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200905<- data.table::fread("C:/Users/user1/Desktop/raw/200905_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200906<- data.table::fread("C:/Users/user1/Desktop/raw/200906_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200907<- data.table::fread("C:/Users/user1/Desktop/raw/200907_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200908<- data.table::fread("C:/Users/user1/Desktop/raw/200908_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200909<- data.table::fread("C:/Users/user1/Desktop/raw/200909_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200910<- data.table::fread("C:/Users/user1/Desktop/raw/200910_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200911<- data.table::fread("C:/Users/user1/Desktop/raw/200911_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata200912<- data.table::fread("C:/Users/user1/Desktop/raw/200912_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201001<- data.table::fread("C:/Users/user1/Desktop/raw/201001_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201002<- data.table::fread("C:/Users/user1/Desktop/raw/201002_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201003<- data.table::fread("C:/Users/user1/Desktop/raw/201003_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201004<- data.table::fread("C:/Users/user1/Desktop/raw/201004_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201005<- data.table::fread("C:/Users/user1/Desktop/raw/201005_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201006<- data.table::fread("C:/Users/user1/Desktop/raw/201006_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201007<- data.table::fread("C:/Users/user1/Desktop/raw/201007_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201008<- data.table::fread("C:/Users/user1/Desktop/raw/201008_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201009<- data.table::fread("C:/Users/user1/Desktop/raw/201009_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201010<- data.table::fread("C:/Users/user1/Desktop/raw/201010_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201011<- data.table::fread("C:/Users/user1/Desktop/raw/201011_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201012<- data.table::fread("C:/Users/user1/Desktop/raw/201012_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201101<- data.table::fread("C:/Users/user1/Desktop/raw/201101_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201102<- data.table::fread("C:/Users/user1/Desktop/raw/201102_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201103<- data.table::fread("C:/Users/user1/Desktop/raw/201103_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201104<- data.table::fread("C:/Users/user1/Desktop/raw/201104_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201105<- data.table::fread("C:/Users/user1/Desktop/raw/201105_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201106<- data.table::fread("C:/Users/user1/Desktop/raw/201106_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201107<- data.table::fread("C:/Users/user1/Desktop/raw/201107_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201108<- data.table::fread("C:/Users/user1/Desktop/raw/201108_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201109<- data.table::fread("C:/Users/user1/Desktop/raw/201109_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201110<- data.table::fread("C:/Users/user1/Desktop/raw/201110_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201111<- data.table::fread("C:/Users/user1/Desktop/raw/201111_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201112<- data.table::fread("C:/Users/user1/Desktop/raw/201112_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201201<- data.table::fread("C:/Users/user1/Desktop/raw/201201_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201202<- data.table::fread("C:/Users/user1/Desktop/raw/201202_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201203<- data.table::fread("C:/Users/user1/Desktop/raw/201203_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201204<- data.table::fread("C:/Users/user1/Desktop/raw/201204_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201205<- data.table::fread("C:/Users/user1/Desktop/raw/201205_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201206<- data.table::fread("C:/Users/user1/Desktop/raw/201206_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201207<- data.table::fread("C:/Users/user1/Desktop/raw/201207_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201208<- data.table::fread("C:/Users/user1/Desktop/raw/201208_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201209<- data.table::fread("C:/Users/user1/Desktop/raw/201209_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201210<- data.table::fread("C:/Users/user1/Desktop/raw/201210_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201211<- data.table::fread("C:/Users/user1/Desktop/raw/201211_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201212<- data.table::fread("C:/Users/user1/Desktop/raw/201212_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201301<- data.table::fread("C:/Users/user1/Desktop/raw/201301_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201302<- data.table::fread("C:/Users/user1/Desktop/raw/201302_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201303<- data.table::fread("C:/Users/user1/Desktop/raw/201303_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201304<- data.table::fread("C:/Users/user1/Desktop/raw/201304_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201305<- data.table::fread("C:/Users/user1/Desktop/raw/201305_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201306<- data.table::fread("C:/Users/user1/Desktop/raw/201306_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201307<- data.table::fread("C:/Users/user1/Desktop/raw/201307_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201308<- data.table::fread("C:/Users/user1/Desktop/raw/201308_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201309<- data.table::fread("C:/Users/user1/Desktop/raw/201309_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201310<- data.table::fread("C:/Users/user1/Desktop/raw/201310_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201311<- data.table::fread("C:/Users/user1/Desktop/raw/201311_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201312<- data.table::fread("C:/Users/user1/Desktop/raw/201312_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201401<- data.table::fread("C:/Users/user1/Desktop/raw/201401_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201402<- data.table::fread("C:/Users/user1/Desktop/raw/201402_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201403<- data.table::fread("C:/Users/user1/Desktop/raw/201403_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201404<- data.table::fread("C:/Users/user1/Desktop/raw/201404_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201405<- data.table::fread("C:/Users/user1/Desktop/raw/201405_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201406<- data.table::fread("C:/Users/user1/Desktop/raw/201406_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201407<- data.table::fread("C:/Users/user1/Desktop/raw/201407_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201408<- data.table::fread("C:/Users/user1/Desktop/raw/201408_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201409<- data.table::fread("C:/Users/user1/Desktop/raw/201409_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201410<- data.table::fread("C:/Users/user1/Desktop/raw/201410_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201411<- data.table::fread("C:/Users/user1/Desktop/raw/201411_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201412<- data.table::fread("C:/Users/user1/Desktop/raw/201412_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201501<- data.table::fread("C:/Users/user1/Desktop/raw/201501_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201502<- data.table::fread("C:/Users/user1/Desktop/raw/201502_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201503<- data.table::fread("C:/Users/user1/Desktop/raw/201503_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201504<- data.table::fread("C:/Users/user1/Desktop/raw/201504_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201505<- data.table::fread("C:/Users/user1/Desktop/raw/201505_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201506<- data.table::fread("C:/Users/user1/Desktop/raw/201506_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201507<- data.table::fread("C:/Users/user1/Desktop/raw/201507_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201508<- data.table::fread("C:/Users/user1/Desktop/raw/201508_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201509<- data.table::fread("C:/Users/user1/Desktop/raw/201509_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201510<- data.table::fread("C:/Users/user1/Desktop/raw/201510_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201511<- data.table::fread("C:/Users/user1/Desktop/raw/201511_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))
rawdata201512<- data.table::fread("C:/Users/user1/Desktop/raw/201512_auto_hr.txt",skip=75,header=FALSE,colClasses=col_classes,na.strings=c('-9991','-9995','-9996','-9997','-9998','-9999'))

#整理
col_names = c('stno','yyyymmddhh','PS01','TX01','RH01','WD01','WD02','PP01','SS01')
col_classes = c('character', 'integer', 'float', 'float', 'integer', 'float','integer', 'float','float')

dataclean = function(x){
  setnames(x, col_names)
  B <- subset(x,x$stno %in% "C0M530") }
C200601 <-dataclean(rawdata200601)
C200602 <-dataclean(rawdata200602)
C200603 <-dataclean(rawdata200603)
C200604 <-dataclean(rawdata200604)
C200605 <-dataclean(rawdata200605)
C200606 <-dataclean(rawdata200606)
C200607 <-dataclean(rawdata200607)
C200608 <-dataclean(rawdata200608)
C200609 <-dataclean(rawdata200609)
C200610 <-dataclean(rawdata200610)
C200611 <-dataclean(rawdata200611)
C200612 <-dataclean(rawdata200612)
C200701 <-dataclean(rawdata200701)
C200702 <-dataclean(rawdata200702)
C200703 <-dataclean(rawdata200703)
C200704 <-dataclean(rawdata200704)
C200705 <-dataclean(rawdata200705)
C200706 <-dataclean(rawdata200706)
C200707 <-dataclean(rawdata200707)
C200708 <-dataclean(rawdata200708)
C200709 <-dataclean(rawdata200709)
C200710 <-dataclean(rawdata200710)
C200711 <-dataclean(rawdata200711)
C200712 <-dataclean(rawdata200712)
C200801 <-dataclean(rawdata200801)
C200802 <-dataclean(rawdata200802)
C200803 <-dataclean(rawdata200803)
C200804 <-dataclean(rawdata200804)
C200805 <-dataclean(rawdata200805)
C200806 <-dataclean(rawdata200806)
C200807 <-dataclean(rawdata200807)
C200808 <-dataclean(rawdata200808)
C200809 <-dataclean(rawdata200809)
C200810 <-dataclean(rawdata200810)
C200811 <-dataclean(rawdata200811)
C200812 <-dataclean(rawdata200812)
C200901 <-dataclean(rawdata200901)
C200902 <-dataclean(rawdata200902)
C200903 <-dataclean(rawdata200903)
C200904 <-dataclean(rawdata200904)
C200905 <-dataclean(rawdata200905)
C200906 <-dataclean(rawdata200906)
C200907 <-dataclean(rawdata200907)
C200908 <-dataclean(rawdata200908)
C200909 <-dataclean(rawdata200909)
C200910 <-dataclean(rawdata200910)
C200911 <-dataclean(rawdata200911)
C200912 <-dataclean(rawdata200912)
C201001 <-dataclean(rawdata201001)
C201002 <-dataclean(rawdata201002)
C201003 <-dataclean(rawdata201003)
C201004 <-dataclean(rawdata201004)
C201005 <-dataclean(rawdata201005)
C201006 <-dataclean(rawdata201006)
C201007 <-dataclean(rawdata201007)
C201008 <-dataclean(rawdata201008)
C201009 <-dataclean(rawdata201009)
C201010 <-dataclean(rawdata201010)
C201011 <-dataclean(rawdata201011)
C201012 <-dataclean(rawdata201012)
C201101 <-dataclean(rawdata201101)
C201102 <-dataclean(rawdata201102)
C201103 <-dataclean(rawdata201103)
C201104 <-dataclean(rawdata201104)
C201105 <-dataclean(rawdata201105)
C201106 <-dataclean(rawdata201106)
C201107 <-dataclean(rawdata201107)
C201108 <-dataclean(rawdata201108)
C201109 <-dataclean(rawdata201109)
C201110 <-dataclean(rawdata201110)
C201111 <-dataclean(rawdata201111)
C201112 <-dataclean(rawdata201112)
C201201 <-dataclean(rawdata201201)
C201202 <-dataclean(rawdata201202)
C201203 <-dataclean(rawdata201203)
C201204 <-dataclean(rawdata201204)
C201205 <-dataclean(rawdata201205)
C201206 <-dataclean(rawdata201206)
C201207 <-dataclean(rawdata201207)
C201208 <-dataclean(rawdata201208)
C201209 <-dataclean(rawdata201209)
C201210 <-dataclean(rawdata201210)
C201211 <-dataclean(rawdata201211)
C201212 <-dataclean(rawdata201212)
C201301 <-dataclean(rawdata201301)
C201302 <-dataclean(rawdata201302)
C201303 <-dataclean(rawdata201303)
C201304 <-dataclean(rawdata201304)
C201305 <-dataclean(rawdata201305)
C201306 <-dataclean(rawdata201306)
C201307 <-dataclean(rawdata201307)
C201308 <-dataclean(rawdata201308)
C201309 <-dataclean(rawdata201309)
C201310 <-dataclean(rawdata201310)
C201311 <-dataclean(rawdata201311)
C201312 <-dataclean(rawdata201312)
C201401 <-dataclean(rawdata201401)
C201402 <-dataclean(rawdata201402)
C201403 <-dataclean(rawdata201403)
C201404 <-dataclean(rawdata201404)
C201405 <-dataclean(rawdata201405)
C201406 <-dataclean(rawdata201406)
C201407 <-dataclean(rawdata201407)
C201408 <-dataclean(rawdata201408)
C201409 <-dataclean(rawdata201409)
C201410 <-dataclean(rawdata201410)
C201411 <-dataclean(rawdata201411)
C201412 <-dataclean(rawdata201412)
C201501 <-dataclean(rawdata201501)
C201502 <-dataclean(rawdata201502)
C201503 <-dataclean(rawdata201503)
C201504 <-dataclean(rawdata201504)
C201505 <-dataclean(rawdata201505)
C201506 <-dataclean(rawdata201506)
C201507 <-dataclean(rawdata201507)
C201508 <-dataclean(rawdata201508)
C201509 <-dataclean(rawdata201509)
C201510 <-dataclean(rawdata201510)
C201511 <-dataclean(rawdata201511)
C201512 <-dataclean(rawdata201512)
#彙整
datacombine <-rbind(C200601,C200602,C200603,C200604,C200605,C200606,C200607,C200608,C200609,C200610,C200611,C200612,C200701,
      C200702,
      C200703,
      C200704,
      C200705,
      C200706,
      C200707,
      C200708,
      C200709,
      C200710,
      C200711,
      C200712,
      C200801,
      C200802,
      C200803,
      C200804,
      C200805,
      C200806,
      C200807,
      C200808,
      C200809,
      C200810,
      C200811,
      C200812,
      C200901,
      C200902,
      C200903,
      C200904,
      C200905,
      C200906,
      C200907,
      C200908,
      C200909,
      C200910,
      C200911,
      C200912,
      C201001,
      C201002,
      C201003,
      C201004,
      C201005,
      C201006,
      C201007,
      C201008,
      C201009,
      C201010,
      C201011,
      C201012,
      C201101,
      C201102,
      C201103,
      C201104,
      C201105,
      C201106,
      C201107,
      C201108,
      C201109,
      C201110,
      C201111,
      C201112,
      C201201,
      C201202,
      C201203,
      C201204,
      C201205,
      C201206,
      C201207,
      C201208,
      C201209,
      C201210,
      C201211,
      C201212,
      C201301,
      C201302,
      C201303,
      C201304,
      C201305,
      C201306,
      C201307,
      C201308,
      C201309,
      C201310,
      C201311,
      C201312,
      C201401,
      C201402,
      C201403,
      C201404,
      C201405,
      C201406,
      C201407,
      C201408,
      C201409,
      C201410,
      C201411,
      C201412,
      C201501,
      C201502,
      C201503,
      C201504,
      C201505,
      C201506,
      C201507,
      C201508,
      C201509,
      C201510,
      C201511,
      C201512)
#時間
datacombine[, timestamp:=datacombine_timestamp]
dtime <- as.POSIXct(strptime('201610141147', '%Y%m%d%H%M'))
mday(dtime)
yday(dtime)
week(dtime)

datacombine[,timestamp:=as.POSIXct(strptime(datacombine$yyyymmddhh, format='%Y%m%d%H'))]
datacombine[,date:=as.POSIXct(strptime(datacombine$yyyymmddhh, format='%Y%m%d'))]
data_ymdh <- datacombine[hour(datacombine$timestamp) >= 20  & hour(datacombine$timestamp) <=23]
data_ymdh[, year:= data.table::year(timestamp)]
data_ymdh[, month:= data.table::month(timestamp)]
datacombine[, day:= data.table::mday(timestamp)]
# 計算每個月的平均溫度
aggrmonth <- aggregate(TX01 ~ month, data = data_ymdh,mean, na.rm = TRUE)
dim(data_ymdh)
head(data_ymdh)
# 計算每個年的平均溫度
aggryear <- aggregate(TX01 ~ year, data = data_ymdhe,mean, na.rm = TRUE)
#計算每月平均累積降水
aggrrain <- aggregate(PP01 ~ month, data = data_ymdhe,mean, na.rm = TRUE)
#計算每日最低溫平均
aggrday_low <- aggregate(TX01 ~ day, data = datacombine,min, na.rm = TRUE)
mean(aggrday_low$TX01)
#計算每日最高溫平均
aggrdayh_high <- aggregate(TX01 ~ day, data = datacombine,max, na.rm = TRUE)
mean(aggrday_high$TX01)
#計算每日溫平均
aggrday <- aggregate(TX01 ~ day, data = datacombine,mean, na.rm = TRUE)

