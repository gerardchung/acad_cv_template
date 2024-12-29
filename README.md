---
format:
  pdf:
    papersize: <PAPER_SIZE>
    geometry: margin=1in
    fontsize: <FONT_SIZE>
    mainfont: "Lato"  # choose your font
    linestretch: 1.15
    colorlinks: true
    urlcolor: black
execute:
  echo: false
  warning: false
  message: false
---

## Template for Academic CV 

#### YAML header (the first section)
- this section sets global configurations for the CV
- Choose whatever font you want. I usually go to Google Font to download the fonts into your local computer font folder

#### Some functions
- You should not change these functions unless you know what you are doing. 
- `format_publications` function will set up the publications in a consistent formatting.
- Similarly for `create_table` function, this create tables that are consistent in style 

#### read_csv 
- there are two csv files i use to fill in information to load into the cv.
- I prefer to use csv to (1) automate the styling and (2) inputing data into csv is just easier than manually updating the cv

#### Samples

- this is how the template looks like [here](acad_cv_template.pdf)
- this is how my cv looks like [here](cv_2025.pdf)