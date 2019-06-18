

```R
########## DATES ##############
```


```R
thor <- c('1978-06-09')
loki <- c('1989-06-06')
agegap <- thor - loki
```


    Error in thor - loki: non-numeric argument to binary operator
    Traceback:




```R
thor <- as.Date(c('1978-06-09'))
loki <- as.Date(c('1989-06-06'))  
  
agegap <- thor - loki
agegap
```


    Time difference of -4015 days



```R
# 
```
