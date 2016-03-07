## Summary ##
The Lasso is a shrinkage and selection method for linear regression. Lasso4j is a Java implementation of the Lasso L1-constrained fitting for linear regression. This implementation is based on the <a href='http://cran.r-project.org/web/packages/glmnet/index.html'>glmnet R package</a> which is implemented in Fortran.

## Sample Output ##
  * Input data: <a href='http://lasso4j.googlecode.com/svn/trunk/lasso4j/src/test/resources/diabetes.data'>diabetes.data</a>  (source: http://www.stanford.edu/~hastie/Papers/LARS/diabetes.data)
  * glmnet R package output: <a href='http://lasso4j.googlecode.com/svn/trunk/lasso4j/src/test/resources/glmnet-diabetes-result.txt'>glmnet-diabetes-result.txt</a>
  * lasso4j output: <a href='http://lasso4j.googlecode.com/svn/trunk/lasso4j/src/test/resources/lasso4j-output-for-diabetes.txt'>lasso4j-output-for-diabetes.txt</a>

## Sample Usage ##
For using lasso4j, you need to download the jar file from Downloads section and add it to your classpath. For an example usage of the code, see <a href='http://lasso4j.googlecode.com/svn/trunk/lasso4j/src/test/java/edu/uci/lasso/TestLasso.java'>this example</a>.

<br /><br /><br />
Developed by <a href='http://www.ics.uci.edu/~yganjisa'>Yasser Ganjisaffar</a>