+++
title = "The SAMPL6 SAMPLing challenge: Assessing the reliability and efficiency of binding free energy calculations"
date = 2019-04-11T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Andrea Rizzi", "Travis Jensen", "David R. Slochower", "Matteo Aldeghi", "Vytautas Gapsys", "Stefano Bosisio", "Niel M. Henriksen", "Bert L. de Groot", "Alex Dickson", "Julien Michel", "Michael K. Gilson", "Michael R. Shirts", "David L. Mobley", "John D. Chodera" ]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract.
abstract = "Approaches for computing small molecule binding free energies are now regularly being employed by academic and industry practitioners to study receptor-ligand systems and prioritize the synthesis of small molecules for ligand design. Given the variety of methods and implementations available, it is natural to ask how these methods compare to each other in terms of final predictions and convergence rates.Here, we describe the conceptualization and results for the first SAMPLing challenge from the SAMPL series focusing on the assessment of convergence properties and reproducibility of binding free energy methodologies. We provided parameter files and multiple initial geometries for two octa-acid (OA) and one cucurbit[8]uril (CB8) host-guest systems, for which it is computationally feasible to obtain converged binding affinity estimates in a matter of hours or a few days. Participants submitted binding free energy predictions as a function of the computational effort for six different alchemical- and physical-pathway (e.g. molecular dynamics and potential of mean force) methodologies based on GROMACS, AMBER, and OpenMM implementations.For the two small OA binders, the free energy estimates computed with alchemical and potential of mean force approaches show relatively similar variance and bias as a function of the number of energy/force evaluations, with the attach-pull-release (APR) and GROMACS expanded ensemble methodologies performing particularly well. The differences between the methods widen when analyzing the CB8-quinine system, where both the guest size and correlation times are greater. For this system, coupled topologies non-equilibrium switching (CP-NS) obtained the overall highest efficiency followed by Hamiltonian replica exchange (HREX). Among the conclusions emerging from the data, we found that CP-NS convergence can be enhanced by increasing the length of the non-equilibrium protocol, that HREX, while displaying very small variance, can incur into substantial bias that depends on the initial population of the replicas, and that the Berendsen barostat introduces non-negligible artifacts in expanded ensemble simulations. Surprisingly, the results suggest that specifying the forcefield parameters and charges is insufficient to ensure reproducibility to better than \textasciitilde 0.5~kcal/mol. Further work will be required to identify the exact source of these discrepancies.
"

# Summary. An optional shortened abstract.
# summary = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum."

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Source Themes"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides = "example"

# Links (optional).
url_pdf = ""
url_code = "https://github.com/slochower/SAMPLing"
url_dataset = "https://github.com/MobleyLab/SAMPL6"
url_project = "https://github.com/MobleyLab/SAMPL6/tree/master/host_guest/SAMPLing"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  # focal_point = "Smart"
+++

{{% alert note %}}
Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
{{% /alert %}}
