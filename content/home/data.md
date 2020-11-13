+++
widget = "blank"
headless = true  # This file represents a page section.
weight = 40  # Order that this section will appear in.

# ... Put Your Section Options Here (title etc.) ...

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"
+++

# Data

### European Social Survey  



- [ESS-Partyfacts crosswalk](https://github.com/sophieehill/ess-partyfacts-crosswalk): Crosswalk between ESS codes for political parties to Partyfacts ID. Allows you to merge in information from various party-level datasets (Manifesto Project, ParlGov, etc.)

- [ESS cumulative dataset](https://github.com/sophieehill/ess-cumulative): R script to build a cumulative dataset from ESS rounds 1-9, with harmonized variables for vote intention, education, and social class. Also provides an example of using the Partyfacts ID to merge in information from an external dataset: in this case, I use the Manifesto Project data to add a variable for the party family. 