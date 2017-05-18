# Unambiguous Metabolite Identification in High-throughput Metabolomics by Hybrid 1D 1H NMR/ESI MS1 Approach

## Installation Guide

### Prerequisites

* GlassFish 4.1.2 requires **Java EE 7** (JDK 7 minimum).
* Download the [Match_to_Chenomx.zip](https://github.com/EMSL-NMR-EPR/MATLAB-1D_1H_NMR_ESI_MS1-WebApp/blob/master/Match_to_Chenomx.zip) zip archive from this repository, and extract its contents.

### Instructions

The application is built with Java 8. So Java 8 runtime (JRE) must be installed
1.	Download GlassFish, either: glassfish-4.1.2-web.zip or glassfish-4.1.2.zip.
(I recommend Payara over Glassfish, Payara is actively getting bug fixes regularly, it is a derivation of Glassfish, so the interfaces between the two are identical mostly
http://www.payara.fish/downloads, be sure to download the latest Full version)
2.	Install GlassFish (extract the contents of the zip archive): unzip glassfish-4.1.2*zip.
3.	Start GlassFish: glassfish4/bin/asadmin start-domain.
4.	Load the GlassFish console: Go to http://localhost:4848.
5.	If the login screen appears, enter the “admin” for the username, and nothing in the password box, this is the default, it can be changed inside the admin console.
6.	On the "Common Tasks" page, under the "Deployment" heading, click the "Deploy an Application" link.
Instructions for Payara
1.	Click Applications
2.	Click Deploy button
3.	Select Packaged File to Be Uploaded to the Server option and Click Choose File button. Then locate and select Match_to_Chenomx.war file.
4.	Select Web Application for the Type dropdown menu.
5.	Enter metabolomics in Context Root box, this is mandatory because the application is configured to be discovered on http://host:port/metabolomics, 
6.	Can optionally enter a descriptive name for the Application Name field or leave everything else as is.
7.	In the "Deploy Application or Modules" form, under "Location", select the dist/Match_to_Chenomx.war file. Ensure that the "Type" is set to "Web Application". Finally, click the "OK" button at the bottom of the page.
8.	The "Match_to_Chenomx" application should now be listed in the table of "Deployed Applications" on the "Applications" page. Click the "Launch" button to receive a link to the deployed application (e.g., "http://localhost/Match_to_Chenomx", http://localhost:8080/metabolomics).


## How to cite this work

### Citation

> Walker, L. R., Hoyt, D. W., Walker, S. M. II, Ward, J. K., Nicora, C. D., and Bingol, K. (2016) Unambiguous metabolite identification in high-throughput metabolomics by hybrid 1D 1H NMR/ESI MS1 approach. *Magn. Reson. Chem.*, **54**: 998–1003. doi: [10.1002/mrc.4503](http://dx.doi.org/10.1002/mrc.4503).

### BibTeX

```
@article {MRC:MRC4503,
author = {Walker, Lawrence R. and Hoyt, David W. and Walker, S. Michael and Ward, Joy K. and Nicora, Carrie D. and Bingol, Kerem},
title = {Unambiguous metabolite identification in high-throughput metabolomics by hybrid 1D 1H NMR/ESI MS1 approach},
journal = {Magnetic Resonance in Chemistry},
volume = {54},
number = {12},
issn = {1097-458X},
url = {http://dx.doi.org/10.1002/mrc.4503},
doi = {10.1002/mrc.4503},
pages = {998--1003},
keywords = {metabolomics, metabolite identification, human urine, Arabidopsis thaliana, tomato, hybrid 1D 1H NMR/ESI MS1},
year = {2016},
note = {MRC-16-0067.R1},
}
```

## Corresponding author

<dl>
  <dt>Correspondence to:</dt>
  <dd>
    <address>
      Kerem Bingol, Ph.D.,<br/>
      Pacific Northwest National Laboratory,<br/>
      Richland,<br/>
      Washington 99354,<br/>
      United States.
    </address>
  </dd>
  
  <dt>Phone:</dt>
  <dd>
    <a href="tel:+15093717927">509-371-7927</a>
  </dd>
  
  <dt>E-mail:</dt>
  <dd>
    <a href="mailto:kerem.bingol@pnnl.gov">kerem.bingol@pnnl.gov</a>
  </dd>
</dl>
