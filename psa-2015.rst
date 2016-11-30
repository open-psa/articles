
`Session Computer codes`_

.. _Session Computer codes: http://www.psa2015.org/Sessions/Session4-1.pdf

**Multiple Models Support in Probabilistic Safety Assessment Program
RiskA (13033)**

Shanqi CHEN, Jin WANG, Jiawen XU, Fang Wang, Liqin HU

Chinese Academy of Sciences

Probabilistic safety assessment (PSA) programs have been widely used for
the fault tree analyses. However, the fault tree model formats of
different programs are generally different, which will introduce
difficulties in the comparison and verification among these PSA
programs. RiskA, a reliability and probabilistic safety assessment
program developed by FDS Team, can support multiple model formats of
widely used PSA programs. Abundant benchmarks are tested and results are
compared, which verified the accuracy and efficiency of the model
conversion.

**Design and Implementation of Probabilistic Safety Analysis Program B
ased on C/S Architecture (13035)**

Jiawen XU (1, 2), Jin WANG (1), Shanqi Chen (1, 2), Liqin HU (1, 2)

#. Chinese Academy of Sciences,
#. University of Science and Technology of China

Probability safety analysis (PSA) programs are necessary tools for the
PSA analysis of large complicated systems. Architectur e is the basis of
product software systems, the effectiveness and efficiency of the
architect ure design determined the quality and performance of the
product software. Most existing PSA software is standalone. In this
paper, the design and implementation of the new Client/Server (C/S)
architecture developed on the platform of PSA program RiskA will be
introduced in detail. Combining with multilayer software system
structure design method and integrating with module exploring idea, the
new architecture can enhance reliability, efficiency and expandability
of PSA software system.



`Open PSA`_.

.. _Open PSA: http://www.psa2015.org/Sessions/Session16-1.pdf


**The Andromeda Shell and Scripting Interface to Efficiently Treat PSA Models (12023)**

Friedlhuber Thomas (1)  , Mohamed Hibti (2), Antoine Rauzy (3)   


#. EdgeMind S.A.S, France,
#. EDF R&D, France,
#. Ecole Polytechnique, France



Working with large full scope PSA models may require appropriate to
ols to browse the models, to allow their modication, documenta tion
and to per form export/import and merge procedures that cover the
needs of version management and validation processes of large PSA
models or parts of them.  In this paper we introduce a shell based
language that provides appropriate shell commands to handle PSA models
and allow scripting over PSA-Modules for systematic procedures and
batch ope rations. This approach is based on an XML format between
Scandpower RS-PSA format and the Open PSA Model Exchange Format.

The introduction of a shell based language reveals new efficient
opportunities of automating any kind of procedures when working with
PSA models.  Scripts can be developed in a generic way, what all ows
them to remain compact, readable and expressive at the same time.
Their execution is reproducible, debug -able, testable and most
important, ef ficient.  Scripts can be considered for updating
procedures (for instance for updating system fault trees when
generated automatically via arti ficial intelligence tools), or for
comparing and merging versions of a PSA models with divergent paths,
for establishing the events cartography (to highlight dependencies
over specifi c patterns), for revision and review procedures to allow
easy and systematic and incremental search and validate procedures to
ensure a better view of the nested structures within a PSA model and
for easy documenting edition.


**A Method to Compare PSA Models in a Modular PSA (12103)**

Friedlhuber Thomas (1)  , Mohamed Hibti (2), Antoine Rauzy (3)


#. EdgeMind S.A.S, France,
#. EDF R&D, France,
#. Ecole Polytechnique, France


Most Probabilistic Safety Assessment (PSA) models are typically based
on the fault tree and event tree approach . Since decades, these PSA
models serve as important tool for safety demonstration and as support
for regulatory issues. In some industries, for example in nuclear
power plants, PSA models increased in size and complexity over the
recent years as a consequence of the scope extension to external
hazards, new applications and new requirements (due post-Fukushima
insights and recommendations).


Therefore, for the purpose of quality assurance, it is worth to have a
precise log of any model evolution s to guaranty compliance with
standards and to ensure that models refl ect the reality of plants.
However, in the database architecture of currently used PSA tools,
only meta data information can be obtained concerning model modifi
cations. Analysts (users), developers and reviewers may need to have
deep insights on di fferent model transitions (set of modifi cations),
and then go through details in order to verify and justify (for
example to safety authorities) the set of modi fications applied to a
PSA model.  Currently, those activities are performed manually and can
be time-consuming and error-prone since PSA models may contain dozens
of thousands of model objects.

In this article, a method is presented to automatically compare PSA
models.  The method prov ides important feedback to model engineers
for example to verify model modifications applied since an ancient
model state, for checking or diagnosis purposes (for instance to
understand the impact and importance o f individual model modi
fications).  Further, the result (the diff erences) can be used to
automatically generate modifi cation reports to trace and justify
model modifi cations.  Finally, it can serve as preliminary step for
the purpose of model fusion (the "combination" of models) w hich is an
ultimate step to con current modeling. The comparison method has been
implemented in Andromeda, a research software developed at EDF R&D to
develop and test new modeling approaches in a so- called modular PSA".
A modular PSA treats models by smaller pieces (the modules") what
constitutes a crucial paradigm for the comparison method of this
article.



**Use of PSA M odel XML Standard Formats for V&V (12108)**

Enrique Melendez Asensio Roberto Herrero Santos

Consejo de Seguridad Nuclear (Spain)


The Spanish Nuclear regulatory body (CSN) has implemented a regulatory
system inspired by the USNRC Reactor Oversight Process (ROP). As
such, the system makes use of PSA results and insights in several
tasks. Inspection results are assessed by PSA quantification,
determining the consequences of licensee performance deficiencies by
mapping onto a PSA model any failures to comply with rules and
regulations.  A requantification of the model yields the impact of
the performance deficiency in the plant risk. The outcome is used to
t ake decisions on further regulatory actions.  In addition, whenever
applicable, inspection scope is driven by PSA importance, be it the
baseline inspections or special inspections, reactive to events.
This regulatory framework requires PSA information to be disseminated
throughout the organization, even among non PSA experts. A web based
information system has been brought up that presents PSA hypotheses,
methods and results in a consistent manner for all Spanish
plants. Inspectors have ready access to this information tool within
CSN’s internal website.  The information in the web based system
stems from the licensees’ PSA models. Since the Spanish NPPs use
several PSA codes, a common interface to feed the web base
information system is required. T he OpenPSA initiative (http://www.open-psa.org/ ) proposed an XML standard format for PSA
model exchange, dubbed OPSA -MEF.  At CSN, an XML format derived from
the OpenPSA work, suitable for the quantification tools used at CSN
has been the choice.  Mor eover, the OPSA-MEF is a platform for
developing tools that convert PSA models between PSA codes, allowing
the same model to be viewed, modified and quantified by different
programs.  This has been demonstrated by tools developed at CSN.
Furthermore, as reg ulators, CSN staff need s independent views on
licensee models.  These can be best accomplished by in-house tools
that perform batch checks for consistency of the models.
