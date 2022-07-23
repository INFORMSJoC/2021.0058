[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Data for SPC Matching at WPI

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

### WPI Datasets contain three datasets of the actual student to project center (SPC) matching at Worcester Polytechnic Institute (WPI) across three acedemic years including 2017-2018, 2018-2019, and 2019-2020. Each dataset containing in each folder represents each academic year including the following material in four .csv files:

- student_preference.csv contains an |S|x|P| matrix of student preference where an entry (s,p) in index s and column p indicates a preference value of student s at project center p. These values range between 0 and 1.
- project_preference.csv contains an |S|x|P| matrix of project director preference where an entry (s,p) in index s and column p indicates a preference value of project director p on student s. These values range between 0 and 1.
- project_capacity.csv contains the capacity of each project center where each row is a tuple of ProjectID and the corresponding Capacity.
- student_info.csv contains the gender and major of students where each row is a tuple of StudentID, Gender, and Major.

Note: The present matching process requires students to rate each project center in one of three tiers as Very Interested, Interested, or Not Interested, which are assigned student utility weights of 1, 0.5, and 0, respectively. In an effort to increase access, students are required to choose at least three project centers in the Very Interested tier and at least six options in the Very Interested and Interested tiers, combined. However, this requirement was applied after the academic year 2017-2018; moreover, during the process of selecting the final match outcome, administrators removed some project centers that lacked sufficient interest from students. Therefore, the final WPI datasets in the academic years 2018-2019 and 2019-2020 contain some select students where the number of rated project centers does not strictly adhere to the requirement.

## Cite

To cite this data files, please cite the [paper](https://doi.org/10.1287/ijoc.2021.0058) using its DOI and the software itself, using the following DOI.

[![DOI](https://zenodo.org/badge/516552677.svg)](https://zenodo.org/badge/latestdoi/516552677)

Below is the BibTex for citing this version of the code.

```
@article{CacheTest,
  author =        {Wiratchotisatian, Pitchaya},
  publisher =     {INFORMS Journal on Computing},
  title =         {{Data sets: A Comparative Study of Stability Representations for Solving Many-to-One Matching Problems with Utility-Weighted Objectives, Ties, and Incomplete Lists via Integer Optimization} Version v1.0},
  year =          {2022},
  doi =           {10.5281/zenodo.6892615},
  url =           {https://github.com/INFORMSJoC/2021.0058},
}  
```
