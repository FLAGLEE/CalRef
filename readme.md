# CalRef

## Features
- Filter abnormal GNSS satellite ephemeris
- Eliminate the wrong satellite ephemeris 
- Return a list of satellites with wrong ephemeris
- Calculate accurate reference station coordinates
- 
## Input example
  -k D:\\Document\\RTK\\CalRef\\CalRef\\data\\calref.conf -o D:\\Document\\RTK\\CalRef\\sc北斗GEO星历错误\\sc北斗GEO星历错误\\SCDC02_test.pos D:\\Document\\RTK\\CalRef\\sc北斗GEO星历错误\\sc北斗GEO星历错误\\SCDC02.obs D:\\Document\\RTK\\CalRef\\sc北斗GEO星历错误\\sc北斗GEO星历错误\\brdc0350-lqz.21p

## Output example
- Success
  - //有解
- Error
  - //无解
- Error System :navsys=5
  - //剔除错误卫星系统，有解
- Error Satellite List :C01 C02 C03 C04 C05 C18
  - //剔除错误卫星，有解
