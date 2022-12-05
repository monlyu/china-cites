# china-cites
china province cities countries code json / sql 

中国城市代码

filed Name  | field type | field des
------------- | -------------| -------------
uuid     | long   | identity
name     | text   | city name
nameEn   | text   | city pinyin
parentId | long   | parent city provice->city->country 
parents  | text   | provice,city
lat      | double | gps lat
lon      | double | gps lon
idstart  | text   | idcard start with
