#Data Munging Tools Installation Guidelines
###Compiled by Christina Harlwo
###[@cm_harlow](http://twitter.com/cm_harlow), [cmharlow@gmail.com](mailto:cmharlow@gmail.com)

##Installation Guidelines
Each tool and script that I present in the data munging workshop have different installation instructions and require different working environment dependencies. Find more information for installing each tool below, as well as any possible cloud-based options I could find that would make installation and involvement easier. The tools mentioned go from more-GUI (graphical user interface) based to straight programming languages and libraries.

I've also included links to communities and other places with people that can help if installation goes awry. Feel free to ask me as well - my contact information is at the start of this document.

###Google Apps Script Editor

No installation required. Just use the script editor function available via Google Drive projects. Google Scripts is a watered-down version of Javascript, that **changes often with little backward compatibility**. See more information on the Google Script objects, classes, functions in the follow-up documentation links.

Google Apps Script Editor can help with adding data validation functions to various Google Drive products, including sheets.

###OpenRefine

####About
There are a few options depending on your comfort with git/GitHub, the memory available in your working env, and the functionalities you need.

**Easiest option**: Create a RefinePro account if you want to test OpenRefine without installing anything. This is a hosted version of OpenRefine made available with a free 1 month trial: http://refinepro.com/ (use the LODLAM community option when signing up if you'd like to use LODRefine).

**Intermediate option**: Use an installer if you want to run OpenRefine on your computer locally with a starter icon added to your Applications folder. See the installation instructions for the most recent release version here: https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions If you want to then use Linked Open Data and RDF functionalities seen in LODRefine, you'll need to follow these instructions to add that extension: https://github.com/LODLAM/DLF15LODLAM/blob/master/CleaningMetadata/Installation/AddDERIExtension.md

**Dive in the Deep End option**: Clone the most recent OpenRefine version if you’re comfortable with (or want to learn more) Git and Github and compile/run via the command line interface of your choice: https://github.com/OpenRefine/OpenRefine/ If you want to then use Linked Open Data and RDF functionalities seen in LODRefine, you'll need to follow these instructions to add that extension: https://github.com/LODLAM/DLF15LODLAM/blob/master/CleaningMetadata/Installation/AddDERIExtension.md (or, alternatively, ignore this whole paragrapha and just go clone https://github.com/sparkica/LODRefine).

####Help!
The OpenRefine community has lots of great folks who can help you if you get stuck with installation. I’d recommend the following places to start - or, as ever, ask the session leaders.

- [OpenRefine Official Documentation](https://github.com/OpenRefine/OpenRefine/wiki)
- [OpenRefine Google Group](https://groups.google.com/forum/#!forum/openrefine)
- [OpenRefine on Twitter](https://twitter.com/openrefine)

###Python & PyMARC

####Python: Getting Started
Python is a high-level programming language that offers powerful options for data work - though it also offers a relatively steep learning curve. If you’re not already somewhat comfortable with working in a Command Line Interface of your choice, but you want to start working with and learning python for library data munging, check out the following resources:

- [Official Python Beginner’s guide - walks through installing Python on your working environment](https://wiki.python.org/moin/BeginnersGuide/Download)
- [Python Anywhere - a cloud-hosted Python IDE (integrated development environment) with a free, limited option.](https://www.pythonanywhere.com/pricing/)
- [For learning Python before working through the examples mentioned in this session, the Code Academy Python course is good and free.](https://www.codecademy.com/)

####PyMARC
[PyMARC](https://github.com/edsu/pymarc) is a Python library for working with MARC data in python scripts/applications. Once you have Python installed, you then need the Python Installer Package or ‘pip’, which should come already with most current versions of Python. 

Go to the command line interface of your choice and type in: 
```pip install pymarc```. 
This should start installing the PyMARC library. 

####Help!
Learn more about PyMARC at their [GitHub repository](https://github.com/edsu/pymarc) as well as on their [Google Group](https://groups.google.com/forum/#!forum/pymarc).

###Catmandu
####About
[Catmandu](http://librecat.org/Catmandu/) is a series of Perl (another high-level programming language) modules for working with a variety of library data platforms, models, encodings and formats. One of the gems of the Catmandu project is the Fix Language, a domain-specific language for data transformations meant to be easy to read by non-programmers. 

Catmandu requires installing quite a bit of dependencies and can be tricky. There are a few options depending on your comfort with a command line interface and basic programming:

**Easiest option**: Just test the Fix Language in a [virtual Fix Language demo editor offered by the LibreCat Project](http://demo.librecat.org/) (the brilliant folks behind Catmandu). 

**Intermediate option**: Work with Catmandu in a Virtual Machine: https://librecatproject.wordpress.com/2014/12/01/day-1-getting-catmandu/  

**Dive in the Deep End option**: [Install Catmandu locally following the options detailed here](http://librecat.org/Catmandu/#installation), with the caveat that one of this session’s leaders strongly recommends using [PerlBrew](http://perlbrew.pl/) if possible.

####Help!
If you’re having any issues getting started with Catmandu, the committers and developers are very helpful. You can try asking them a question on the LibreCat listserv - or joining to lurk yourself and learn from others’ discussions:

- Mailing list: [librecat-dev@mail.librecat.org](mailto:librecat-dev@mail.librecat.org) 
- Subscribe to or view the [archives of the LibreCat listserv here](http://mail.librecat.org/mailman/listinfo/librecat-dev)

