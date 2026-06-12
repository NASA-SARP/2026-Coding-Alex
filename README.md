# 2026-Coding-Alex

Welcome to SARP coding in 2026! This repository contains coding lessons and resources for the [NASA Student Airborne Research Program (SARP)](https://www.nasa.gov/centers/ames/earthscience/programs/airbornescience/studentairborneresearchprogram) 2026 with Alex.

For the coding lessons component, we will primarily be using files in the [lessons](lessons) folder. 

Please note that this is an active repository and there will be frequent updates. Some of these folders may be empty for now.

## Folders
1) [docs](docs)
2) [lessons](lessons)
3) [problems](problems)
4) [snippets](snippets)

## Lessons

This lesson plan will be updated regularly. Please check back for updates.

Click on the link under each Lesson Name to navigate to the Jupyter Notebook lesson. Click the link under Slides to navigate to the slides used in each lesson as an introduction to the concepts.

| # | Lesson | New Python Libraries| Intro Slides|
|-----|:--------------|:---------|:---------|
| 1 | [Python Building Blocks](lessons/01_building_blocks/01_building_blocks.ipynb) | | |
| 2 | [Tabular Data](lessons/02_tabular_data/02_tabular_data.ipynb) | `pandas` | [Intro](docs/intro_lesson_02.pdf)|
| 3 | [Vector Data](lessons/03_vector_data/03_vector_data.ipynb) | `shapely`, `geopandas` | [Intro](docs/intro_lesson_03.pdf)|
| 4 | [Gridded Data](lessons/04_gridded_data/04_gridded_data.ipynb) | `xarray` | |
| 5 | [Raster Data](lessons/05_raster_data/05_raster_data.ipynb) | `rasterio`, `numpy`| [Intro](docs/intro_lesson_06.pdf)|


## Setup

During the in-person lessons, we will mainly be working with Jupyter Lab via CryoCloud. The simplest option is to download the lesson.zip, unzip, and upload it to your CryoCloud Desktop.

If you prefer to use git, you can download this repo using:

`git clone https://github.com/NASA-SARP/2026-Coding-Alex.git`

Given the active lesson updates, you may need to regularly fetch (`git fetch`) and merge updates (`git pull`) into your clone of the repo to have the latest version of the lessons.

If you want to get a single lesson you can use:

`git checkout main -- lessons/01_building_blocks/01_building_blocks.ipynb`

However, please note that each lesson additionally contains folders `images` and `data` which contain files used in the class. If you checkout a single lesson file, you will additionally need to make a copy of these folders in the same directory as your copy of the lesson file. 

## Acknowledgements

This repository was created by [Alex Saunders](https://alex-saunders00.github.io/) and borrows heavily from the NASA SARP Programming Lessons _["Python Programming for Earth Science Researchers"](https://nasa-sarp.github.io/sarp_lessons/)_ created by Rachel Wegener. The contents of this repository were also inspired by past NASA SARP coding mentors.


