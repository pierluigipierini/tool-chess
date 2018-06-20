# tool-chess

TABLE OF CONTENTS
 1 - OVERVIEW
 2 - WEBSITE
 3 - DOWNLOAD
 4 - INSTALLATION
 5 - SYSTEM REQUIREMENTS
 6 - RELEASE NOTES
 7 - LICENSE
 8 - DEVELOPPER RESOURCES
 9 - SUPPORT
10 - GETTING STARTED GUIDELINES
11 - EXAMPLES
12 - ADDITIONAL INFORMATION


1 - OVERVIEW
PolarSys CHESS implements the CHESS UML profile, a specialization of the Modeling and Analysis of Real-Time and Embedded Systems (MARTE) profile, by producing extensions to Papyrus that  provide component-based engineering methodology and tool support for the development of high-integrity embedded systems in different domains like satellite on board systems.
The CHESS tool environment is composed by:
1.    a MARTE/UML profile,
2.    an extension to the Papyrus UML graphical editor that supports the notion of design views,
3.    a model validator that assesses the well-formedness of the model before model transformations can be undertaken, and
4.    a set of model to model and model to text transformations, the former for the purpose of model-based schedulability and dependability analysis and the latter for code generation toward multiple language targets.
 
2 - WEBSITE
https://www.polarsys.org/chess
 
3 - DOWNLOAD
https://www.polarsys.org/chess/download.html
 
4 - INSTALLATION
The PolarSys CHESS Eclipse full distribution can be installed simply uncompressing it.
The Polarsys CHESS is an Eclipse plug-in that can be installed using the standard update-site feature; detailed instructions are available on the website.
 
5 - SYSTEM REQUIREMENTS
Windows 7 x86 64-bit Oracle Java 7 or
Ubuntu 14.04 x86 64-bit Open JDK 7;
Eclipse Luna with the following plugins in place: Acceleo Core SDK, ATL SDK, QVT Operational SDK, Papyrus
 (update available on newer Eclipse versions)

6 - RELEASE NOTES
Latest Release: 0.10.0, 2016-10-31

Review Description:
This release provides several major features:
New profile for dependability
Tool support for State Based Analysis and Failure Logic Analysis.
Support for contract based modelling; integration with OCRA FBK tool for contract based    analysis.
New Instance View to navigate and check/create timing properties for software component instances.
Support for multiple software to hardware deployment modelling and analysis.
New specialized properties tabs.
Several bugs fixed.
 
Older release: 0.9.0, 2015-07-30    
 
7 - LICENSE
Eclipse Public License - v 1.0 (see http://www.eclipse.org/org/documents/epl-v10.php)
 
8 - DEVELOPPER RESOURCES
Source Repositories: http://git.polarsys.org/c/chess/chess.git
Clone: git://git.polarsys.org/gitroot/chess/chess.git, ssh://git.polarsys.org/gitroot/chess/chess.git
 
You can use the code from these repositories to experiment, test, build, and create patches, issue pull requests, etc. (Review With Gerrit Browse Repository)
 
9 - SUPPORT
Wiki: https://wiki.polarsys.org/CHESS
Forum: https://polarsys.org/forums/index.php/f/9/
Mailing list subscription: https://dev.polarsys.org/mailman/listinfo/chess-dev
 
10 - GETTING STARTED GUIDELINES
https://www.polarsys.org/chess/start.html

11 - EXAMPLES
Producer-Consumer: http://download.polarsys.org/chess/models/ProtectedOperationSample.zip
IndustrialDrive: http://download.polarsys.org/chess/models/IndustrialDrive.zip
Wheel Braking System (example about contract-based design): http://download.polarsys.org/chess/models/WBS.zip


12 - ADDITIONAL INFORMATION
CHESS-ML Profile: https://www.polarsys.org/chess/publis/CHESSMLprofile.pdf
User Guide: https://www.polarsys.org/chess/publis/CHESSToolset_UserGuide.pdf

