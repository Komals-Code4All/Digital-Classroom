# Digital Classroom 

The idea here is to have a general website for displaying teaching materials.
<hr>

The <strong>TOP LEVEL <strong> index.html is the gateway to all different <em>subjects</em>. For example, subjects could include HTML, JavaScript and Python.

At the <strong>SUBJECT LEVEL</strong> each subject is a separate website, in its own folder, with its own index.html and assets folder. In addition, there is a folder for all the individual lessons, held in individual HTML files.

The subject's main <em>index.html<em> page is made up of a nav-bar and an iFrame. The nav-bar has links to the individual lessons. When clicked, the lesson will will appear in the iFrame.

The diagram below may help explain this structure.
<pre>       
                                        --------------
Top Level                               : index.html : -->  ----------------- 
                                        --------------      : asset folder  : --> CSS folder
                                               :            -----------------     Images folder
                                               :
                                _________________________________
                                :              :                :
Subject Level               ---------       ---------       ----------
(folders)                   : HTML  :       :  JS   :       : PYTHON :
                            ---------       ---------       ----------
                                :
                                :
Chapter Level   ---------------------------------           -----------------------------
                : HTML Lessons' Folder          :           : Python Lessons' Folder    :
                :-------------------------------:           :---------------------------:
                : 00_HTML_Intro.html            :           : 00_PYT_Intro.html         : 
                : 10_HTML_InputOutput.html      :           : 10_PYT_InputOutput.html   :
                : 20_HTML_Variables.html        :           : 20_PYT_Variables.html     : 
                : 30_HTML_DataStructures.html   :           : 30_PYT_DataStructs.html   : 
                : 32_HTML_Arrays.html           :           : 32_PYT_Arrays.html        :
                : 34_HTML_Objects.html          :           : ... etc                   :
                : 40_HTML_IF_THEN.html          :           -----------------------------
                : 50_HTML_Loops.html            :
                : ....etc                       :
                ---------------------------------
</pre>