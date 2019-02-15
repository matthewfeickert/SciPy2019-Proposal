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

- First Name: Giordon
- Last Name: Stark
- Email: gstark@cern.ch
- Country: United States
- Organization: University of California Santa Cruz Santa Cruz Institute for Particle Physics (UCSC SCIPP)
- Web page: https://giordonstark.com/
- Corresponding Author: No

## Title and Abstract
> The title and the abstract should be entered as plain text, they should not contain HTML elements.

### Title

pyhf: a pure Python statistical fitting library from the high energy physics community with tensors and autograd

### Abstract

> c.f. the [Planning for your proposal submission?](https://github.com/matthewfeickert/SciPy2019-Proposal/blob/feature/add-talk-proposal/info_page.md#planning-for-your-proposal-submission) information page

#### Description

In experimental high energy physics statistical fitting tools have been implemented almost entirely in C++. In particular, the "HistFactory" p.d.f. template [CERN-OPEN-2012-016], used extensively in the 2012 discovery of the Higgs boson, has only existed in implementations in the C++ based ROOT analysis framework. pyhf [DOI: 10.5281/zenodo.1464139] is a pure-Python implementation of that statistical model for multi-bin histogram-based analysis with interval estimation based on the asymptotic formulas of "Asymptotic formulae for likelihood-based tests of new physics" [arxiv:1007.1727]. pyhf supports modern computational graph libraries such as TensorFlow and PyTorch as computational backends in order to make use of features such as auto-differentiation and GPU acceleration.

#### Audience

- Who is the intended audience for your talk?

This talk would be of particular interest to scientists (experimentalists and theorists alike), engineers, and statisticians (though Frequentist methods are used Bayesians will still be interested) who are looking to use machine learning frameworks for statistical analysis in Python.

- What, specifically, will attendees learn from your talk?

Regardless of audience background, they will also see how they can use JSON to define an expressive human and machine readable schema for statistical models and implement those models in modern machine learning frameworks.

#### Outline (25 Minute Talk + 2 Minutes for Questions)

##### Introduction (5 Minutes)

- Introduce pyhf and the development team
- Give lightning overview of experimental high energy physics: the community, challenges, and goals
- Highlight the close relationship between high energy physics and the data science and machine learning communities (e.g., Institute for Research and Innovation in Software for High Energy Physics (IRIS-HEP), Hammers & Nails - Machine Learning & HEP Workshop)

##### Statistics and Python in High Energy Physics (5 Minutes)

- Introduction of statistical challenges in high energy physics
- Methods used (to great success) in the past
- The rise of Python in the high energy physics community

##### pyhf: What does it provide? (10 Minutes)

- pip installable library from PyPI
- Implementation of asymptotic interval estimation algorithm based on profile likelihood test-statistic
- Pure JSON schema for statistical models
- Suite of CLI options and helper tools
- Machine learning frameworks for computational backends
   - TensorFlow, PyTorch, and more
- Automatic differentiation (autograd)
- GPU acceleration

##### Looking forward and lessons for the community (5 Minutes)

- Use in the high energy physics community in analyzing the full ATLAS dataset from the Large Hadron Collider
- Improvements with GPUs and distributed computing with Dask
- Applying lessons from our statistical model (HistFactory) to general statistical modeling with machine learning frameworks

##### Questions (2 Minutes)

- Will prepare supplementary slides for anticipated questions

#### Notes

This is my first SciPy proposal, and if accepted my first Python conference of any kind. I have presented on pyhf for the development team multiple times in the high energy physics community, but this is the first time that it would be presented to the broader scientific Python community.

Most of my talks are technical talks in the high energy physics community (for example: Matthew Feickert, "Searches for boosted low mass resonances decaying to b-quarks with the ATLAS detector", Higgs Couplings, Tokyo, Japan, November 29, 2018. https://indico.cern.ch/event/732102/contributions/3188460/) however I have also given talks to the high energy physics software community. I was also a guest on Michael Kennedy's "Talk Python to Me" podcast, Episode #144: Machine Learning at the Large Hadron Collider (https://talkpython.fm/episodes/show/144/machine-learning-at-the-large-hadron-collider)

- pyhf on GitHub: https://github.com/diana-hep/pyhf
- pyhf documentation: https://diana-hep.org/pyhf/
- List of talks given on pyhf: https://diana-hep.org/pyhf/talks.html
   - Most relevant: Matthew Feickert, Lukas Heinrich, Giordon Stark, and Kyle Cranmer. pyhf: a pure python implementation of histfactory with tensors and autograd. DIANA Meeting - pyhf, October 2018. https://indico.cern.ch/event/759480/
- Scientific publications that have used pyhf: Lukas Heinrich, Holger Schulz, Jessica Turner, and Ye-Ling Zhou. Constraining A₄ Leptonic Flavour Model Parameters at Colliders and Beyond. 2018. https://arxiv.org/abs/1810.05648

## Keywords
> Type a list of keywords (also known as key phrases or key terms), one per line to characterize your submission. You should specify at least three keywords.

- Physics
- Statistics
- Fitting
- SciPy
- NumPy
- TensorFlow
- PyTorch
- MXNet
- Auto-Differentiation

## Other Information and Files

### Type of submission
> Please indicate if your submission should be considered for a talk slot or poster.

**Talk**

### Please select the topic of your submission..*

> **Main tracks include:**
>
> - General
> - Data Driven Discoveries (machine learning and data science)
> - Open Source Communities (Sustainability)
>
> **Minisymposia include:**
>
> - Science Communication through Visualization
> - Neuroscience and Cognitive Science
> - Image Processing
> - Earth, Ocean, Geo and Atmospheric Science

- [ ] General
- [x] **Data Driven Discoveries (machine learning & data science)**
- [ ] Open Source Communities
- [ ] Science Communication through Visualization
- [ ] Neuroscience and Cognitive Science
- [ ] Image Processing
- [ ] Earth, Ocean, Geo and Atmospheric Science
- [ ] SciPy Tools Plenary Session Mini Talk

### Please provide a short summary of your topic..*
> The summary should be less than 100 words and should be suitable to be used as a description in the online program.

In experimental high energy physics statistical fitting tools have been implemented almost entirely in C++. pyhf is a pure-Python implementation of the "HistFactory" statistical model, used to discover the Higgs boson, for multi-bin histogram-based analysis with interval estimation based on "Asymptotic formulae for likelihood-based tests of new physics" [arxiv:1007.1727]. pyhf supports modern computational graph libraries such as TensorFlow and PyTorch as computational backends to make use of features such as auto-differentiation and GPU acceleration. pyhf demonstrates a flexible and robust model for large binned statistical fits to meet the statistical challenges of the high energy physics community.

### Paper. (Optional)
> You are welcome to upload additional information or a paper to support your proposal.

None.
