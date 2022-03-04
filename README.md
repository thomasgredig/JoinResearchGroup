# Join Research Group

How to Join the [Gredig Molecular Thin Film Laboratory](https://web.csulb.edu/~tgredig/) 


## Checklist

Basic research in the [Gredig Molecular Thin Film Lab](https://web.csulb.edu/~tgredig/) is open to both undergraduate and graduate students. The most important pre-requisite is **interest**. Preparation to become a successful contributor begins with a few skills that can be learned and should be approached in this sequence.

- contact the group leader, [Dr. Gredig](https://web.csulb.edu/~tgredig/group.html)
- contact the [CNSM safety office](https://web.csulb.edu/colleges/cnsm/safety/) and complete all general safety training and quizzes.
- read research literature (see [below](#Literature))
- familiarize yourself with some of the [research instruments](https://web.csulb.edu/~tgredig/facilities.html) and their Standard Operating Procedures (SOP)
- organize yourself with the analysis software (see [below](#analysis-software))
- read about ethics and proper conduct (see [below](#ethics-and-conduct))
- submit a photo for the [Lab Group](https://web.csulb.edu/~tgredig/group.html) page
- acknowledge and agree on the research lab responsibilities, expectations and duties (form from Dr. Gredig)
- discuss mentor-mentee compact and setup regular meetings
- agree on the research questions / proposal / tasks
- get a bound notebook and record observations
- create a comprehensive PPTx file (see [below](#comprehensive-powerpoint-file))
- pick up lab keys through the [Department Office](https://www.csulb.edu/physics-astronomy/contact)
- enroll in one of the courses to get university, such as [PHYS 496](http://catalog.csulb.edu/search_advanced.php?cur_cat_oid=6&search_database=Search&search_db=Search&cpage=1&ecpage=1&ppage=1&spage=1&tpage=1&location=33&filter%5Bkeyword%5D=phys+496) - Special Problems in Physics, PHYS 498, [PHYS 697](http://catalog.csulb.edu/search_advanced.php?cur_cat_oid=6&search_database=Search&search_db=Search&cpage=1&ecpage=1&ppage=1&spage=1&tpage=1&location=33&filter%5Bkeyword%5D=phys+directed) - Directed Research or [PHYS 698](http://catalog.csulb.edu/search_advanced.php?cur_cat_oid=6&search_database=Search&search_db=Search&cpage=1&ecpage=1&ppage=1&spage=1&tpage=1&location=33&filter%5Bkeyword%5D=phys+thesis) - Thesis
- consider the Phyiscs, B.S. with [Materials Science Option](http://catalog.csulb.edu/search_advanced.php?cur_cat_oid=6&search_database=Search&search_db=Search&cpage=1&ecpage=1&ppage=1&spage=1&tpage=1&location=33&filter%5Bkeyword%5D=applied+physics+option)
- consider the Physics, M.S. [Applied Physics Option](http://catalog.csulb.edu/search_advanced.php?cur_cat_oid=6&search_database=Search&search_db=Search&cpage=1&ecpage=1&ppage=1&spage=1&tpage=1&location=33&filter%5Bkeyword%5D=applied+physics+option)
- consider enrolling in [PHYS 445 / 545](https://web.csulb.edu/~tgredig/teaching.html) - Advanced Experimental Methods in Materials Science
- conduct research and present your [research at the CNSM](https://web.csulb.edu/colleges/cnsm/sas/symposium/), co-publish your research with Dr. Gredig
- apply for [scholarships](https://www.csulb.edu/student-affairs/financial-aid-and-scholarships-office), [REUs](https://www.nsf.gov/crssprgm/reu/), and graduate programs.

For M.S. projects, you should also read the [Master's Thesis Guidelines](https://github.com/thomasgredig/MSthesis-Guidelines).


## Literature

Research happens at the cutting-edge of knowledge. Knowing the current research questions is an on-going tasks. Use one of the literature search engines to explore your topics:

- [Web of Science](https://csulb.idm.oclc.org/login?url=https://www.webofknowledge.com/WOS)
- [Google Scholar](https://scholar.google.com/)
- [arXiv](https://arxiv.org/archive/cond-mat)

Read specific articles to expand your vocabulary and learn about specific examples, including:

- Gredig: [Asymmetric grain distribution in phthalocyanine thin films](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.80.174118)
- Gredig: [ Height-Height Correlation Function to Determine Grain Size in Iron Phthalocyanine Thin Films](http://web.csulb.edu/~tgredig/research/hhcf.php)
- Gredig: [Tunable Finite-Sized Chains to Control Magnetic Relaxation](https://arxiv.org/abs/1612.07397)
- Giessibl: [Advances in atomic force microscopy](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.75.949)
- Evangelisti: [Magnetic properties of α-iron(II) phthalocyanine](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.66.144410)
- Bartolome: [Magnetism of Metal Phthalocyanines](https://link.springer.com/chapter/10.1007/978-3-642-40609-6_9)
- Vargas: [Helical spin structure in iron chains with hybridized boundaries ](https://aip.scitation.org/doi/abs/10.1063/5.0022926)
- Colesniuc: [Exponential behavior of the Ohmic transport in organic films](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.83.085414)

Take notes when reading the article; look at the motivation (first paragraph), and the message that the article carries; so that you can refer to previous data on which you build forward.



## Analysis Software

All data must be analyzed reproducibly; anyone, at any later time, must be able to reproduce the analysis. Therefore, it is important to label, and name files systematically.

**Important:** read [Data File Conventions](https://github.com/thomasgredig/MSthesis-Guidelines#file-system)

Briefly, the format is as follows (Example: `20170501_BiThermal_SF_VSM_SF20170426_MvsH-5K.DAT`):

- Date_Project_Initials_Tool_Sample_RunInfo.csv

Therefore, each sample has exactly 5 underscores. The tools to analyze the data (reproducibly) should be open-source, so that they can be used by anyone. We recommend learning the following tools:

 * [Zotero](https://www.zotero.org/) for references, see [Zotero Documentation](https://www.zotero.org/support/)
 * [R](https://www.r-project.org/) for graphs and tables, see [R scientific reproducibility](https://swcarpentry.github.io/r-novice-gapminder/)
 * [LaTeX](https://www.latex-project.org/) for Thesis, learn how to use on [OverLeaf](https://www.overleaf.com/learn)

Several libraries specific to our data analysis are publicly available via Github, including:

- [nanoscopeAFM](https://github.com/thomasgredig/nanoscopeAFM) for AFM data analysis
- [quantumPPMS](https://github.com/thomasgredig/quantumPPMS) for Quantum Design PPMS data analysis
- [rigakuXRD](https://github.com/thomasgredig/rigakuXRD) for XRD data analysis
- [nanomasterNTE](https://github.com/thomasgredig/nanomasterNTE) for graphing sample fabrication parameters
- [tiffTagReader](https://github.com/thomasgredig/tiffTagReader) for reading TIFF AFM data tags and images
- [checkRAWfolder](https://github.com/thomasgredig/checkRAWfolder) for data validation and analysis



## Ethics and Conduct

Ethical behavior has a long tradition in science and is necessary for its continuation. The [University has an office](http://web.csulb.edu/divisions/students/judicial_affairs/) of student conduct and ethical development, which outlines policies. Misconduct in science centers around reporting research results that are fabricated, plagiarized, and or falsified, see [APS Ethics](http://www.aps.org/programs/education/ethics/). Appropriate conduct includes


- proper record-keeping;
- truthful, careful handling and [reporting of data](https://www.aps.org/programs/education/ethics/data/index.cfm);
- responsible, respectful interactions with peers and subordinates;
- adherence to journal publication guidelines, including proper recognition of research contributions.

We can use some basic rules from sociologist [Robert Merton](https://en.wikipedia.org/wiki/Robert_K._Merton) (1910 - 2003) who is known for his work on "unintended consequences". The Mertonian norms provide a guide for doing scientific research. Using the mnemonic CUDOS, the scientific principles should follow *Communalism, Universalism, Disinterestedness, Originality, and Skepticism*.



## Comprehensive Powerpoint File


Keep a lengthy comprehensive powerpoint file. It should include data more or less in chronological order at this point. It includes photos with details. It is not important to keep it organized, but rather it is important to keep it clean and updated. Regularly, add details, data, information, and observations. It should contain 100 - 300 slides. The slides can include photos of samples, personal reviews and snippets of literature, graphs from results, calculations from the analysis, schematics and plans. Use the *notes* section to add folder, filenames, and other information pertinent to the graphs. Photos and data files may additionally need to be stored in the RAW folder.

## Goals

Joining an experimental condensed matter research group means that you can learn a variety of skills. Depending on your interest, you may want to focus on some of those skills:

- practical skills to run new scientific instrumentation and learn about standard operating procedures
- learn computational skills, modeling, graphing using software, such as R, ggplot2, LaTeX, etc.
- design components, construct apparati, 3D print, fix instruments, calibrate and maintain equipment


## Exercises


