+++
title = "Escaping Atom Types in Force Fields Using Direct Chemical Perception"
date = 2018-10-11T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin"]

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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Journal of Chemical Theory and Computation, 14*(11)"
publication_short = ""

# Abstract.
abstract = "Traditional approaches to specifying a molecular mechanics force field encode all the information needed to assign force field parameters to a given molecule into a discrete set of atom types. This is equivalent to a representation consisting of a molecular graph comprising a set of vertices, which represent atoms labeled by atom type, and unlabeled edges, which represent chemical bonds. Bond stretch, angle bend, and dihedral parameters are then assigned by looking up bonded pairs, triplets, and quartets of atom types in parameter tables to assign valence terms and using the atom types themselves to assign nonbonded parameters. This approach, which we call indirect chemical perception because it operates on the intermediate graph of atom-typed nodes, creates a number of technical problems. For example, atom types must be sufficiently complex to encode all necessary information about the molecular environment, making it difficult to extend force fields encoded this way. Atom typing also results in a proliferation of redundant parameters applied to chemically equivalent classes of valence terms, needlessly increasing force field complexity. Here, we describe a new approach to assigning force field parameters via direct chemical perception. Rather than working through the intermediary of the atom-typed graph, direct chemical perception operates directly on the unmodified chemical graph of the molecule to assign parameters. In particular, parameters are assigned to each type of force field term (e.g., bond stretch, angle bend, torsion, and Lennard–Jones) based on standard chemical substructure queries implemented via the industry-standard SMARTS chemical perception language, using SMIRKS extensions that permit labeling of specific atoms within a chemical pattern. We use this to implement a new force field format, called the SMIRKS Native Open Force Field (SMIRNOFF) format. We demonstrate the power and generality of this approach using examples of specific molecules that pose problems for indirect chemical perception and construct and validate a minimalist yet very general force field, SMIRNOFF99Frosst. We find that a parameter definition file only ∼300 lines long provides coverage of all but <0.02% of a 5 million molecule drug-like test set. Despite its simplicity, the accuracy of SMIRNOFF99Frosst for small molecule hydration free energies and selected properties of pure organic liquids is similar to that of the General Amber Force Field, whose specification requires thousands of parameters. This force field provides a starting point for further optimization and refitting work to follow."

# Summary. An optional shortened abstract.
# summary = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum."

# Digital Object Identifier (DOI)
doi = "10.1021/acs.jctc.8b00640"

# Is this a featured publication? (true/false)
featured = true

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
url_pdf = "https://pubs.acs.org/doi/10.1021/acs.jctc.8b00640"
url_code = "https://github.com/openforcefield"
url_dataset = ""
url_project = ""
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
