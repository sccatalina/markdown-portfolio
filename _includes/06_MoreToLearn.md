# Tables

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

# Separate Code Blocks
```
Anything written in this **paragraph** will not be _formatted_ even if it would normally be recognized in this setting. :taco:
```

# Syntax Highlighting
More info: https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks
  ```sh
  github-learning-lab ~/Projects/recipe-repository
  $ git init
  Initialized empty Git repository in /Users/github-learning-lab/Projects/recipe-repository/.git/
  ```
  ## Using `\```python` will highlight Python keywords
  ```python
  import pandas as pd
  # This is a comment in Python
  my_message = "Hello World"
  print(my_message)
  ```
  
  ## Using `\```r` will highlight R keywords
  ```r
  library(ggplot2)
  # This is a comment in R 
  x <- 3
  y = TRUE
  # Defining a function
 diam <- function(w){
  (2/2.54) * (w/(0.92*(4/3)*pi))^(1/3)
  }
  ```
  
# Summary dropdown
<details>
  <summary>Drop down list</summary>

  This is the content of the drop down list. It can include anything: text, lists, tables, etc. <br>
  Here's a table:
  First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
 
  And here's a list: 
  - [x] Create new file 06_MoreToLearn.md
  - [x] Try examples covered in the issue
  - [ ] Commit new file

</details>
