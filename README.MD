# Digital Classroom 

The idea here is to have a general website for displaying teaching materials.
<hr>

The top level <em>index.html</em> is the portal to all 'SUBJECTS' to be taught. For example, subject could include HTML, CSS, JavaScript and Python.

Each subject has its own separate website, containing another high-level <em>index.html</em> and a folder contain HTML files of individual chapters. The subject's index.html contains a nav-bar and an iFrame. The nav-bar gives links to the individual chapters. When clicked the chapter html will appear in the iFrame. 



<pre>       

Top Level                   INDEX.HTML
                            ==========

Subject Level           ---------       ---------       ----------
                        : HTML  :       :  CSS  :       : PYTHON :
                        ---------       ---------       ----------



Chapter Level   --------------         
                : Intro.html :    
                -------------       



</pre>