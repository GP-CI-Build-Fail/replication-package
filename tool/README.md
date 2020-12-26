# General info
This toolkit is a powerful library/API written in Java that can detect Travis CI skipped commits applied in the history of a Java/Ruby/PHP project.
For a detailed description of the tool and its associated research work, you can refer to the following research papers:
* Detecting CI Skip Commits Using Multi-objective Evolutionary Search: An Industrial Case Study
# How to use it ?
This toolkit needs a Github project that uses Travis CI to work. We recommend to launch it with Java10.
1. To launch the analysis of a project, you have to define:
	1. the project URL: it can be the Github URL or a the local directory to the GIT project.
	2. the commit hash to be analysed
	3. Decision to work with cross-project option i.e. using existing rules generated from our database (TRUE/FALSE)
2. The toolkit displays the recommendation in the command line console.
3. To get more details, the user can have a look at the explanation (a PDF file)
# Example of usage
Then you can use this tool based on a cross-project prediction, for example :
```
java -jar gp_ci_skipper.jar https://github.com/GrammarViz2/grammarviz2_src 7383e4cb28925f0c3406d7f9fcf0b338f8133864 T
```
# Final instruction
Please keep the directory *lib* along with the jar file. It contains the libraries and files required to launch our tool.

