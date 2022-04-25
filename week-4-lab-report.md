# Lab Report #2

## Error #1
* For the first error, when running the code it would continue in an infinite while loop until we run out of memory to run the program.
* Below is the code change that was made to fix this infinite while loop error. This if statement would check if the current index is blank and not the first line in order to break out of the while loop after checking all lines for websites.
* Link to input file used to prompt for correction of error. [Link to test file](https://github.com/redagent750/markdown-parser/blob/main/test-file.md)
<br/>

![Image](error1codechange.png)

* Below are the errors that were shown before fixing the code.
<br/>

![Image](terminal1error.png)

* Below is the terminal after fixing the issue of the infinite loop.
<br/>

![Image](error1fixed.png)

* The symptom is the while loop within the program kept running until it ran out of space. The bug would be how this while loop is coded to keep running forever since nothing breaks it out. This causes the while loop to forever run until it runs out of memory, which is the only reason why it stops. 

---
## Error #2
* For the second error, when a test file is read for websites only, it also return images as if it was reading websites.
* Below is the code change made in order to have images not be read as websites since both formats are similar in nature.

