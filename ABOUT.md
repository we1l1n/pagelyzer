Pagelyzer 
====================================================================

### What does Pagelyzer do?

Pagelyzer is a tool which compares two web pages versions and decides if they are similar or not.

It is based on:
* a web page segmentation algorithm
* a combination of structural and visual comparison methods embedded in a statistical discriminative model,
* a visual similarity measure designed for Web pages that improves change detection,
* a supervised feature selection method adapted to Web archiving.

We train a Support Vector Machine model with vectors of similarity scores between successive versions of pages. The trained model then determines whether two versions, defined by their vector of similarity scores, are similar or not.

### What are the benefits for the end user?

A list of benefits Pagelyzer brings to the end user:

* Crawler optimization e.g discovering new crawl strategies based on patterns

* Quality assurance for crawlers, for example, by comparing the live version of the page with the just crawled one.

* Detecting format obsolescence following to evolving technologies, is the rendering of web pages are identique visually by using different versions of the browser or different browsers

* Archive maintenance, different operations like format migration can change the archived page versions renderings.

### Who is the intended audience?

Pagelyzer is for:

* Content holders national libraries
* Institutions that are insterested in web archiving
* Institutions that want to start web archiving
* Web archivists
* Archive managers
* Digital preservation specialists


### Examples
The rendering issues due to format obsolescence within the archive and monitor technological
landscape can be detected by the comparison of web pages. This scenario aims at finding possible 
solutions such as using of image comparison to detect rendering errors within web archives(compare 
reference snapshots of web pages in different browser versions.


The quality of the web crawlers can be also tested by comparing the crawled version of the page with the page online just after crawling. 

### Authors

Responsable Workpackage:

* Matthieu CORD/UPMC
* Stéphane GANÇARSKI/UPMC

Contributors:

* Andrés Sanoja <andres.sanoja@lip6.fr> (web page segmentation, content based)
* Marc Law <marc.law@lip6.fr> ( supervised framework, image based, svm, marcalizer)
* Zeynep Pehlivan <zeynep.pehlivan@lip6.fr> (general info)

Contributed but not working anymore for the project
* Alexis Lechervy <alexis.lechervy@lip6.fr> 
* Myriam Ben Saad <myriam.ben-saad@lip6.fr>
* Carlos Sureda <carlos.sureda@lip6.fr>
* Jordi Creus <jordi.creus@lip6.fr>

LIP6 / Université Pierre et Marie Curie


Important Note:
----------------
Some parts of this package are adapted from the BrowserShot project developed by IM, France. https://github.com/sbarton/browser-shot-tool-mapred


Publications
-----------

* A. Sanoja and S. Gançarski. Block-o-Matic: A Web Page Segmentation Framework. Paper accepted for oral presentation in the International Conference on Multimedia Computing and Systems (ICMCS'14). Morroco, April 2014.

* Sanoja A., Gançarski S. "Block-o-Matic: a Web Page Segmentation Tool and its Evaluation". BDA. Nantes, France. 2013.http://hal.archives-ouvertes.fr/hal-00881693/

* Saad M.B., Gançarski S., Pehlivan Z.. A Novel Web Archiving Approach based on Visual Pages Analysis. In 9th International Web Archiving Workshop (IWAW), ECDL 2009

* Sanoja, Gançarski S. "Yet another Web Page Segmentation Tool". Proceedings iPRES 2012. Toronto. Canada, 2012

* Pehlivan Z., Saad M.B. , Gançarski S..Understanding Web Pages Changes. DEXA (1) 2010: 1-15

* M. Teva Law, C. Sureda, N. Thome, S. Gançarski, M. Cord. Structural and Visual Similarity Learning for Web Page Archiving, Workshop CBMI 2012

Blog Posts:

* SCAPE QA Tool: Technologies behind Pagelyzer - I Support Vector Machine
http://www.openplanetsfoundation.org/blogs/2014-02-07-scape-qa-tool-technologies-behind-pagelyzer-i-support-vector-machine

* SCAPE QA Tool: Technologies behind Pagelyzer - II Web Page Segmentation
http://www.openplanetsfoundation.org/blogs/2014-02-12-scape-qa-tool-technologies-behind-pagelyzer-ii-web-page-segmentation


### Credits
* This work was partially supported by the SCAPE project. The SCAPE project is co-funded by the European Union under FP7 ICT-2009.4.1 (Grant Agreement number 270137)
* 