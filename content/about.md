# _Bioconductor_

The mission of the Bioconductor project is to develop, support, and
disseminate free open source software that facilitates rigorous and
reproducible analysis of data from current and emerging biological assays.
We are dedicated to building a diverse, collaborative, and welcoming
community of developers and data scientists.


[Scientific][], [Technical][] and [Community][]
Advisory Boards provide project oversight.

[R]: http://www.r-project.org
[Technical]: technical-advisory-board/
[Scientific]: scientific-advisory-board/
[Community]: community-advisory-board/


## Release and core development

The _Bioconductor_ [release version](/packages/release/bioc/) is updated
twice each year, and is appropriate for most users. There is also a
[development version](/packages/devel/bioc), to which new features and
packages are added prior to incorporation in the release. A large
number of [meta-data packages](/packages/release/data/annotation)
provide pathway, organism, microarray and other annotations.

The _Bioconductor_ project started in 2001 and is overseen by a [core
team](/about/core-team/), based primarily at [Roswell Park Comprehensive Cancer
Center](https://www.roswellpark.org), and by other members coming
from US and international institutions. A [Community Advisory Board][Community] 
and a [Technical Advisory Board][Technical] of key participants 
meets monthly to support the _Bioconductor_ mission by coordinating 
training and outreach activities, developing strategies to ensure long-term 
technical suitability of core infrastructure, and to identify and enable 
funding strategies for long-term viability. 
A [Scientific Advisory Board][Scientific] including external
experts provides annual guidance and accountability.

Key citations to the project include Huber et al., 2015 [Nature
Methods 12:115-121][1] and Gentleman et al., 2004 [Genome Biology
5:R80][2]

[1]: http://www.nature.com/nmeth/journal/v12/n2/abs/nmeth.3252.html
[2]: https://genomebiology.biomedcentral.com/track/pdf/10.1186/gb-2004-5-10-r80.pdf

## _Bioconductor_ Packages

Most _Bioconductor_ components are distributed as [R
packages](http://cran.r-project.org/doc/FAQ/R-FAQ.html#R-Add_002dOn-Packages).
The functional scope of [Bioconductor packages](/packages/release/bioc/)
includes the analysis of DNA microarray, sequence, flow, SNP, and other data.

## Project Goals

The broad goals of the _Bioconductor_ project are:

* To provide widespread access to a broad range of powerful statistical
  and graphical methods for the analysis of genomic data.
* To facilitate the inclusion of biological metadata in the analysis of
  genomic data, e.g. literature data from PubMed, annotation data from
  Entrez genes.
* To provide a common software platform that enables the rapid development
  and deployment of extensible, scalable, and interoperable software.
* To further scientific understanding by producing high-quality
  [documentation](/help/package-vignettes/) and reproducible research.
* To [train](/help/course-materials/) researchers on computational and
  statistical methods for the analysis of genomic data.

## Main Project Features

* **The R Project for Statistical Computing**. Using
  [R](http://www.r-project.org) provides a broad range of advantages
  to the _Bioconductor_ project, including:
  * A high-level interpreted language to easily and quickly prototype
    new computational methods.
  * A well established system for packaging together software with
    documentation.
  * An object-oriented framework for addressing the diversity and
    complexity of computational biology and bioinformatics problems.
  * Access to on-line computational biology and bioinformatics data.
  * Support for rich statistical simulation and modeling activities.
  * Cutting edge data and model visualization capabilities.
  * Active development by a dedicated team of researchers with a
    strong commitment to good documentation and software design.

* **Documentation and reproducible research**. Each [Bioconductor
  package](/packages/release/bioc/) contains one or more
  [vignettes](/help/package-vignettes/), documents that provide a
  textual, task-oriented description of the package's functionality.
  Vignettes come in several forms. Many are "HowTo"s that demonstrate
  how a particular task can be accomplished with that package's software.
  Others provide a more thorough overview of the package or discuss general
  issues related to the package.

* **Statistical and graphical methods**. The _Bioconductor_ project
  provides access to powerful statistical and graphical methods for
  the analysis of genomic data.
  [Analysis packages](/packages/release/bioc/) address
  [workflows](/packages/release/workflows/) for analysis of
  oligonucleotide arrays, sequence analysis, flow cytometry. and other
  high-throughput genomic data.  The
  [R package system](http://cran.r-project.org/doc/FAQ/R-FAQ.html#R-Add_002dOn-Packages)
  itself provides implementations for a broad range of
  state-of-the-art statistical and graphical techniques, including
  linear and non-linear modeling, cluster analysis, prediction,
  resampling, survival analysis, and time-series analysis.

* **Annotation**. The _Bioconductor_ project provides software for
  associating microarray and other genomic data in real time with
  biological metadata from web databases such as GenBank, Entrez genes
  and PubMed ([annotate](/packages/release/bioc/html/annotate.html)
  package).  Functions are also provided for incorporating the results
  of statistical analysis in HTML reports with links to annotation web
  resources.  Software tools are available for assembling and
  processing genomic annotation data, from databases such as GenBank,
  the Gene Ontology Consortium, Entrez genes, UniGene, the UCSC Human
  Genome Project
  ([AnnotationDbi](/packages/release/bioc/html/AnnotationDbi.html)
  package).  [Annotation data packages](/packages/release/data/annotation/)
  are distributed to provide mappings between different probe
  identifiers (e.g. Affy IDs, Entrez genes, PubMed). Customized
  annotation libraries can also be assembled.

* **Bioconductor short courses**. The _Bioconductor_ project has developed a
  program of [short courses](/help/course-materials/) on software and
  statistical methods for the analysis of genomic data. Courses have been
  given for audiences with backgrounds in either biology or statistics. All
  [course materials](/help/course-materials/) (lectures and computer labs)
  are available on this site.

* **Open source**. The _Bioconductor_ project has a commitment to full
  open source discipline, with distribution via a public git
  (version control) server. Almost all contributions exist under an
  open source license. There are many different reasons why open
  source software is beneficial to the analysis of microarray data and
  to computational biology in general. The reasons include:
  * To provide full access to algorithms and their implementation
  * To facilitate software improvements through bug fixing and software
    extension
  * To encourage good scientific computing and statistical practice by
    providing appropriate tools and instruction
  * To provide a workbench of tools that allow researchers to explore and
    expand the methods used to analyze biological data
  * To ensure that the international scientific community is the owner of
    the software tools needed to carry out research
  * To lead and encourage commercial support and development of those tools
    that are successful
  * To promote reproducible research by providing open and accessible tools
    with which to carry out that research (reproducible research is distinct
    from independent verification)

* **Open development**. Users are encouraged to become developers, either
  by contributing
  [Bioconductor compliant packages](/developers/package-guidelines/)
  or documentation. Additionally _Bioconductor_ provides a mechanism for
  linking together different groups with common goals to foster
  collaboration on software, often at the level of shared development.

## Code of Conduct

Please refer to the [Bioconductor Code of Conduct][coc]

[coc]: code-of-conduct/