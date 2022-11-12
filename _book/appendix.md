# (APPENDIX) Appendix {-}



# R programming

R is a popular programming language in biomedicine field. 


```r
#Color Format
colFmt = function(x,color){
  outputFormat = knitr::opts_knit$get("rmarkdown.pandoc.to")
  if(outputFormat == 'latex')
    paste("\\textcolor{",color,"}{",x,"}",sep="")
  else if(outputFormat == 'html')
    paste("<font color='",color,"'>",x,"</font>",sep="")
  else
    x
}
```

### <font color="DD0000"> The coursera on R programming </font> 
<center>![](images/appendix/Coursera_R.png){width=70%}</center>
- Lecturer: *Dr*. Roger D. Peng, Johns Hopkins University
- URL: [https://www.coursera.org/learn/r-programming](https://www.coursera.org/learn/r-programming)

### <font color="DD0000"> Learn R on codecademy </font> 
<center>![](images/appendix/Learn_R.png){width=70%}</center>
- Lecturer: *Dr*. XX, XX University
- URL: [https://www.codecademy.com/learn/learn-r](https://www.codecademy.com/learn/learn-r)

### <font color="DD0000"> Data Science: R Basics </font> 
<center>![](images/appendix/Harvard_R.png){width=70%}</center>
- Lecturer: *Dr*. XX, XX University
- URL: [Data Science: R Basics](https://www.edx.org/course/data-science-r-basics?source=aw&awc=6798_1668191183_10d4db98964f4e5f819646ecb14b17ab&utm_source=aw&utm_medium=646197&utm_content=text-link&utm_term=646197_CodeSpaces)

### <font color="DD0000"> Data Analysis with R </font>
<center>![](images/appendix/Duke_R.png){width=70%}</center>
- Lecturer: *Dr*. XX, Duke University
- URL: [Data Analysis with R](https://www.coursera.org/specializations/statistics?irclickid=0iwUmb3yOxyNTz-SQH2S-VEXUkDSmuwcPXp8QI0&irgwc=1&utm_medium=partners&utm_source=impact&utm_campaign=3311133&utm_content=b2c)

# Python programming

Python is a popular programming language. 


```python
import unittest

def fun(x):
    return x + 1

class MyTest(unittest.TestCase):
    def test(self):
        self.assertEqual(fun(3), 4)
```


<font color='red'>MY RED TEXT</font>

# Rstudio course

# Docker course
