# [SciPy 2019](https://www.scipy2019.scipy.org/) Submission Instructions

## Author 1

- First Name: Matthew
- Last Name: Feickert
- Email: mfeickert@gmail.com
- Country: United States
- Organization: Southern Methodist University
- Web page: http://www.matthewfeickert.com/
- Corresponding Author: Yes

## Author 2

- First Name: Lukas
- Last Name: Heinrich
- Email: lukas.heinrich@cern.ch
- Country: Germany
- Organization: CERN
- Web page: http://www.lukasheinrich.com/
- Corresponding Author: No

## Author 3

- First Name: Giordon Stark
- Last Name: Stark
- Email: gstark@cern.ch
- Country: United States
- Organization: University of California Santa Cruz Santa Cruz Institute for Particle Physics (UCSC SCIPP)
- Web page: https://giordonstark.com/
- Corresponding Author: No

## Title and Abstract
> The title and the abstract should be entered as plain text, they should not contain HTML elements.

### Title

pyhf: a pure python implementation of histfactory with tensors and autograd

### Abstract

> Your placement in the program will be based on reviews of your abstract. This should be a roughly 500 word outline of your presentation. This outline should concisely describe software of interest to the SciPy community, tools or techniques for more effective computing, or how scientific Python was applied to solve a research problem. A traditional background/motivation, methods, results, and conclusion structure is encouraged but not required. Links to project websites, source code repositories, figures, full papers, and evidence of public speaking ability are encouraged.
> - In your abstract, be sure to include answers to some basic questions:
>   - Who is the intended audience for your talk?
>   - What, specifically, will attendees learn from your talk?
> - Ensure that your talk will be relevant to a broad range of people. If your talk is on a particular Python package or piece of software, it should useful to more than a niche group.
> - Include links to source code, articles, blog posts, or other writing that adds context to the presentation.
> - If you've given a talk, tutorial, or other presentation before, include that information as well as a link to slides or a video if they're available.
> - SciPy talks are generally 25 minutes with 2-3 minutes for questions. Please keep the length of time in mind as you structure your outline.

> wc -w 134

**FINISH ONCE HAVE HAD SLEEP**
In experimental high energy physics statistical fitting tools have been implemented almost entirely in C++. In particular, the "HistFactory" p.d.f. template [CERN-OPEN-2012-016], used extensively in the 2012 discovery of the Higgs boson, has only existed in implimentations in the C++ based ROOT framework. pyhf [DOI: 10.5281/zenodo.1464139] is a pure-Python implementation of that statistical model for multi-bin histogram-based analysis and its interval estimation is based on the asymptotic formulas of "Asymptotic formulae for likelihood-based tests of new physics" [arxiv:1007.1727]. pyhf supports modern computational graph libraries such as TensorFlow and PyTorch in order to make use of features such as auto-differentiation and GPU acceleration.

- Who is the intended audience for your talk?

Of particular interest to computational natural scientists and statisticians who are looking to use machine learning frameworks for statistical analysis

- What, specifically, will attendees learn from your talk?

pyhf demonstrates a flexible and robust model for large binned statistical models.

<!-- The HistFactory p.d.f. template [CERN-OPEN-2012-016] is per-se independent of its implementation in ROOT and it is useful to be able to run statistical analysis outside of the ROOT, RooFit, RooStats framework. pyhf is a pure-python implementation of that statistical model for multi-bin histogram-based analysis and its interval estimation is based on the asymptotic formulas of "Asymptotic formulae for likelihood-based tests of new physics" [arxiv:1007.1727]. pyhf supports modern computational graph libraries such as TensorFlow and PyTorch in order to make use of features such as auto-differentiation and GPU acceleration. -->

## Keywords
Type a list of keywords (also known as key phrases or key terms), one per line to characterize your submission. You should specify at least three keywords.

- Physics
- Statistics
- Fitting
- TensorFlow
- PyTorch

## Other Information and Files

### Type of submission
> Please indicate if your submission should be considered for a talk slot or poster.

**Talk**

### Please select the topic of your submission..*

**Main tracks include:**
General
Data Driven Discoveries (machine learning and data science)
Open Source Communities (Sustainability)

**Minisymposia include:**
Science Communication through Visualization
Neuroscience and Cognitive Science
Image Processing
Earth, Ocean, Geo and Atmospheric Science

- [ ]General
- [x] Data Driven Discoveries (machine learning & data science)
- [ ] Open Source Communities
- [ ] Science Communication through Visualization
- [ ] Neuroscience and Cognitive Science
- [ ] Image Processing
- [ ] Earth, Ocean, Geo and Atmospheric Science
- [ ] SciPy Tools Plenary Session Mini Talk

### Please provide a short summary of your topic..*
> The summary should be less than 100 words and should be suitable to be used as a description in the online program.
> wc -w: 92

In experimental high energy physics statistical fitting tools have been implemented almost entirely in C++. pyhf [DOI: 10.5281/zenodo.1464139] is a pure-Python implementation of the statistical model for multi-bin histogram-based analysis used to discover the Higgs boson and its interval estimation is based on the asymptotic formulas of "Asymptotic formulae for likelihood-based tests of new physics" [arxiv:1007.1727]. pyhf supports modern computational graph libraries such as TensorFlow and PyTorch in order to make use of features such as auto-differentiation and GPU acceleration. pyhf demonstrates a flexible and robust model for large binned statistical fits.

### Paper. (Optional)
You are welcome to upload additional information or a paper to support your proposal.

None.
