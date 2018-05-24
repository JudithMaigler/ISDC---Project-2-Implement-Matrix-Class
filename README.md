# ISDC-Project-2-Implement-Matrix-Class

In this project you will implement a Matrix class in Python. Specifically, you will implement the following methods:

class Matrix:
  def determinant(self):
      # your code

  def trace(self):
      # your code

  def inverse(self):
      # your code

  def transpose(self):
     # your code

  # Overloaded operators

  def __add__(self,other):
    # your code

  def __sub__(self,other):
    # your code

  def __mul__(self,other):
    # your code

## Reviewer Instructions

Your project workspace will contain several files. We recommend that you open all of these files except for datagenerator.py and test.py.

You can ignore datagenerator.py and test.py, which you won't need to modify

1) matrix.py - This contains the beginnings of a Matrix class (which you will complete) as well as some helper functions zeroes and identity. This is the file you will be doing most of your work in.
2) matrix_playground.ipynb - A notebook that imports your Matrix class and calls the test code. You may find it useful to use this notebook as a place to use the matrix math code you will write in matrix.py.
3) matrix_cheat_sheet.ipynb - A Jupyter notebook with a glossary, explanation of matrix notation and list of matrix equations. Use this as a reference when filling out the methods in the Matrix class!
4) kalman_filter_demo.ipynb - You don't need to do anything with this notebook but you may find it interesting. Once your matrix class is working properly, the KF implemented here will actually work!
