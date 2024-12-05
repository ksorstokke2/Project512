This repository contains Kyle Sorstokke's completed DATA 512 course project, with analysis of Albuquerque fires,
air quality, and respiratory health.

The actual analysis is split between two Jupyter notebooks entitled part1 and part2. These notebooks contain all code
used in the project, as well as documentation and relevant visualizations and output. The part1 notebook also contains responses
to the common analysis assignment.

The folder entitled healthData contains all downloaded files for the NHAMCS data used in my respiratory health calculations.
These are titled by year and saved in .sav format.

The folder entitled IntData holds intermediate data files created during my analysis. These files hold my fire estimates,
air quality estimates, fire predictions, and cleaned and merged annual health data.

Licensing and sources are described in the LICENSE markdown.

Reproducibility Guide:

All data needed for reproducibility can be obtained through the API calls in part1.ipynb or where part2.ipynb loads the healthData folder.
Part 1 should be run before part 2, since 2 imports some of the intermediate files created from variables in part 1.
