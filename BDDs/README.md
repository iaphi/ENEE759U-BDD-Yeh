## Makefile

```bash
#
# Steps to compile the utitlies provided herein
#
# Origin by Daniel Gomez-Prado
# 2013
# Modified by Cunxi Yu
# 2021

# By Hung-Yu Yeh
# 2024
# Please follow the original step and preceed to blif2bdd to get the midification

#
# automatic form
#------------------------------------------------------------------------
#
Step 1)
Make sure the cudd_location file containes one single line with the full path
to the cudd package 2.5.0

Step 2)
type make distclean

Step 3) 
type make

All directorires should have been compiled and all executables can be found
within each folder.


#
# manual form
#------------------------------------------------------------------------
#
Step 1)
Enter the cudd package 2.5.0 and type make

Step 2)
Make sure the cudd_location file containes one single line with the full path
to the cudd package 2.5.0

Step 3)
Enter each individual directory, except the folders cudd-2.5.0 and test, and type make
```
