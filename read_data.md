
#############################################################################
##                                                                         ##
##                       CCTV 설치 현황 데이터                             ##
##                                                                         ##
#############################################################################
## inital settings
  options(digit=16)
  setwd("C:/Users/Administrator/Dropbox (오픈메이트)/오픈메이트의 팀 폴더/고객사/경기도/2016 지속가능한 빅데이터 분석서비스 제공 사업/")

## read.package
  library(data.table)
  library(dplyr)
  library(reshape2)
  library(stringr)
  library(foreign)
  library(maptools)
  library(sp)
  library(rgeos)
  library(raster)
  library(rgdal)
  library(shapefiles)
  
## read data

library(data.table)
CCTV_org <- fread("02.분석수행-01.데이터/CCTV/1_지자체_CCTV설치현황/CCTV현황.csv")

library(foreign)
data <- read.dbf("/data.dbf")

