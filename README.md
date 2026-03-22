# PERCs4homeschoolersinNC

Public Education Resources for Homeschoolers in North Carolina

> [!NOTE]
> This dataset is a best-effort compilation at a single point in time. To contribute data for updates or changes, open a pull-request on this github repo or send an email to [Christy Batts](https://github.com/christybatts). 

## Description

This repository is a dataset of 394 publicly-available policies collected from federal, state, and local education agencies regarding public education resources and homeschooled students in North Carolina in 2025. Policy documents were found from federal, state, and 115 local education agency webpages and within school board policies. Within these 394 documents, there are 484 policies regarding an array of resources.


### Columns

The `Source` column indicates the author of the policy where federal and state are aggregated under a single label but where individual districts are specifically named.

The `Type` column indicates the resource type by category. The possible categories are: 
- sports
- driver's education course
- extracurricular activities
- K-12 dual enrollment in core academic classes
- eligibility determination/IEP/504 evaluation
- special needs services
- proctoring/testing services
- free or reduced price meals
- access to school space
- other

The `Status` column indicates if the policy is `inclusive`, `exclusive`, or `ambiguous` of homeschooled students. Policies labeled inclusive were those that specifically allowed homeschooled students’ participation or access to the resource. Those labeled exclusive specifically disallowed homeschooled students’ participation or access. Those labeled ambiguous did not name homeschooled students specifically, but alluded to participation or exclusion of nonpublic school students or did not specifically qualify participation by school enrollment.

If the URL in the `Link` column is not longer active, please use Internet Archive's The Wayback Machine: https://web.archive.org/


## Definitions

Public Educational ResourCes (PERCs) are resources that are generally made available by state and local educational institutions to K–12 students. State and local educational resources are, but are not limited to, public funds, materials, curriculum, services, and expertise developed, managed, or distributed by or through publicly funded educational service providers (Hirsch, 2019). 

For this datase, PERC providers are federal, state, and local education agencies (LEA) and are specific to North Carolina. They include but not limited to: the Department of Public Instruction (DPI); the Division of Non-Public Education (DNPE); the North Carolina State Education Athletic Association (NCHSAA); North Carolina State Education Assistance Authority (NCSEAA); and North Carolina Community Colleges (NCCC).

Homeschooled students are K-12 students who receive their education primarily outside a public or private school and are not enrolled in either a public or private school. Homeschooled students may or may not be included in a registered homeschool with the Division of Non-Public Education (DNPE) and may or may not be of compulsory age (NCGS 115C-563). North Carolina homeschool registration is only mandated for students of compulsory age (7-16), and this regulation is not enforced. 


## Purpose

This dataset was created as part of a larger study in which survey and interview data was also collected. 
If you are interested in the full study, please contact [Christy Batts](https://github.com/christybatts).

Homeschool parents in North Carolina have access to some PERCs, primarily through their local public school districts, but also through some state and federal agencies. To learn what public education resources were available to homeschool parents, a document analysis was conducted in the summer months of 2025 which produced this dataset.

 
## Methods

Because public educational goods and services are often reserved for students enrolled in public education, any reference challenging this assumed requirement may be found in public educational policies and regulations. Therefore educational policies across the whole state concerning homeschooled students including, state legislation, Department of Public Instruction and Division on Non-Public Education policies, and local school board policies and website content were collected. 

Using key-word-in-finder and search tools, the keywords homeschool (-er, -ed, -ing), and home school were used to search for relevant policies. Selection criteria was that the written policy or practice was from a local public educational institution or state agency, referred to education resources, and was pertinent to homeschool students either by explicit inclusion, exclusion, or ambiguous language. 

Content analysis is a method for systematically and objectively evaluating text, such a policy (Hsieh & Shannon, 2005; Schreier, 2012). Furthermore, content analysis complements constructivist grounded theory by working with large amounts of data to reach theoretical saturation (Cho & Lee, 2014). The broader study underwhich this dataset was collected used a mixed-methods constructivist grounded theory. Policies were coded by resource type, for example: CCP, NCVPS, college, curriculum, proctoring, counseling, IEP, academics, extracurriculars, driver’s education, and other. Resources were then coded by status: inclusive, exclusive, or ambiguous. Dates were recorded whenever possible. 

Policies were read for inclusive or exclusive language. For example, from a preliminary look at five LEAs board policy documents, policies, driver’s education and dual enrollment were most likely to apply to homeschool students, even without the use of the indicated keywords mentioned previously. Therefore, as the analysis progressed, greater insight was gained about how policies were written, prompting iterative searches as patterns in policies emerged. For example, an inclusive federal-level JROTC policy was not identified until halfway into the analysis; at this point, previously reviewed districts were revisited to specifically examine their JROTC policies and to determine if they mirrored the inclusive federal policy. Additional archival documents were sought when open-ended survey responses or interview participants referenced a specific resource not yet identified through the document analysis. In such cases, key terms were used to locate the relevant resources, and the corresponding policy documents were added to the dataset. 

There were more policies than policy documents due to multiple types of resources being mentioned in one policy document. For example, on one webpage titled “Homeschool Partnership,” Surry County Schools include homeschooled students in six public education resources: proctoring, extracurriculars, driver’s education, K-12 dual enrollment, sports, and IEP evaluation (Surry County Schools, 2025).

This study was conducted with the approval of North Carolina State University’s Institutional Review Board (IRB), ensuring compliance with the greater research community’s ethical standards, including regulations protecting the welfare, rights, and privacy of research participants (OHRP, 2021).


## Limitations

It is unknown if practices differ from written policy. This study did not systematically capture such discrepancies unless they arose through the interview data. 

State level documents were limited to North Carolina. District level was limited to the 115 local education agencies in North Carolina. Not included were charter and tribal schools. 

No policies were found for the following resource categories: curriculum, gifted programming, hearing or vision screening, or counseling services. Therefore, these resource categories are not included in the `Type` column.


## License and Usage

This dataset contains publically available documents and is available for public and non-commercial reuse. Attribution to this dataset should use the reference below.

See the [LICENSE](./LICENSE.txt) document for particulars about the CC-BY-NC license.


### Suggested Reference

> Batts, C. (2026). Public Education Resources for Homeschoolers in North Carolina. https://github.com/christybatts/PERCs4homeschoolersinNC (\<Git commit\>)
