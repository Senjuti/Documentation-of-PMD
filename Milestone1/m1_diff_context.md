diff --git a/m1-context.md b/m1-contextv1.1.md
index 94aff38..b182263 100644
--- a/m1-context.md
+++ b/m1-contextv1.1.md
@@ -18,7 +18,9 @@ External entities on which PMD depends and their responsibilities are as follows
 
 * Code to be analysed : PMD scans source code directly to find the flaws
 
-* IDEs: They use PMD as plug-ins and after integration, they can run PMD to find bugs directly on their repositories. [5]
+* IDEs' PMD Plugins : These are separate Open Source projects, which uses PMD in their libraries and provide integration of PMD with IDEs.
+
+* IDEs: They use the plug-ins and after integration, they can run PMD to find bugs directly on their repositories. [5]
 
 * Command line: PMD can be run through command line. In this case, the following languages are supported - Java, Ecmascript (JavaScript), JSP, PLSQL, Vm (Apache Velocity), Xml and Xsl. [6]
 
@@ -32,9 +34,9 @@ External entities on which PMD depends and their responsibilities are as follows
 
 * GitHub: It allows contributors to fork the source code of PMD and update it. [8]
 
+Context view diagram of PMD is:
 
-
-Context view diagram of PMD has been attached as an image file.
+![PMD_Context_View](ContextViewPMD.png)
 
 #Bibliography
 
@@ -53,8 +55,3 @@ Context view diagram of PMD has been attached as an image file.
 [7] http://sourceforge.net/projects/pmd/
 
 [8] https://github.com/pmd/pmd
-
-
-
-
-
