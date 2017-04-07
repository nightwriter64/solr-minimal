# solr-minimal
This repository contains the current build of Apache Solr where all of the packages
that have licenses considered by many companies to be "non-permissive" have been
removed.

These are primarily found in the "contrib" directory so if you wish to use those
plugins you will have to go to the full distribution as can be found at:


    http://lucene.apache.org/solr/

The overall objective with this binary is to provide a distribution that limits
the licenses to one of the following: Apache, MIT, BSD

Note that some of the "offending" packages essentially have a BSD license, but
unfortunately they do not use the exact BSD license text so many license scanners
pick this up as "Other" or "Unknown license" even though they are clearly BSD
compatible. Sadly, to most lawyers, BSD-Like is the same thing as NOT BSD.
