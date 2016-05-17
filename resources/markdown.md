##[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)  

###Text Formatting
bold: `**bold**`  **bold**  
italic:  `*italic*` *italic*  
italic:  `_italic_` _italic_  

---

###Reference
In a markdown file on GitHub, to see how it was formatted, click on "raw" on upper right corner.

---

###Line Breaks
How to add line breaks:  
1.  can enclose text in triple back quotes  
2.  add two spaces to end of line 

---

###Links
Text for link:  
```Here's an inline link to [Google](http://www.google.com/).```  
Rendered link:  
Here's an inline link to [Google](http://www.google.com/).  

---

###Block Code, Language-specific 

####python

Block code that is non-specific:  
```
print "hello world!"
print "hello moon"
```

Block code that is **python**-specific:  
```python
print "hello world!"
print "hello moon"
```

####bash or console

Block code that is non-specific:  
```
$ git status
$ git remote -v
```

Block code that is **bash**-specific:  
```console
$ git status
$ git remote -v

$ ps awx | grep mongo
```

####sql

Block code that is non-specific:  
```
SELECT * FROM Customers WHERE Country='Sweden';
```

Block code that is **sql**-specific:  
```sql
SELECT * FROM Customers WHERE Country='Sweden';
```

####Yes, this works for scores of other languages:  [Syntax highlighting in markdown](https://support.codebasehq.com/articles/tips-tricks/syntax-highlighting-in-markdown) 

---

###Tables in Markdown
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

---

###Practice Examples

####Data Science Trivia 

####Q1.  
What is the most installed language in the world?  
- Python
- SAS
- R
- Spark
- Javascript

>>REPLACE THIS TEXT WITH YOUR RESPONSE

-

####Q2.  
In hypothesis testing, we use the t score when the sample size is < 30 and the populations SD is unknown; else we use the Z score. 
What is the distribution of t-squared?
 * Normal
 * F
 * Chi-squared
 * Beta
 * Bivariate Normal

>>REPLACE THIS TEXT WITH YOUR RESPONSE

***

####Q3.  
In the scikit-learn's official source repo, about how many issues are outstanding? (go ahead and check out their page)  
1. 7  
2. 70  
3. 700  
4. 7000  

>>REPLACE THIS TEXT WITH YOUR RESPONSE

---
