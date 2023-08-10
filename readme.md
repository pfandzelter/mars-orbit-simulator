# Mars Orbit Constellation Simulator

A fork of [Ben-Kempton/SILLEO-SCNS](https://github.com/Ben-Kempton/SILLEO-SCNS) for Mars satellite constellations.

## Citation

If you use this software in a publication, please cite it as:

### Text

T. Pfandzelter and D. Bermbach, **Can Orbital Servers Provide Mars-Wide Edge Computing?**, 1st ACM MobiCom Workshop on Satellite Networking and Computing (SatCom '23), Madrid, Spain. Association for Computing Machinery, New York, NY, USA. October, 2023.

### BibTeX

```bibtex
@inproceedings{pfandzelter2023mars,
    author = "Pfandzelter, Tobias and Bermbach, David",
    title = "Can Orbital Servers Provide Mars-Wide Edge Computing?",
    booktitle = "Proceedings of the 1st ACM MobiCom Workshop on Satellite Networking and Computing",
    pages = "to appear",
    month = oct,
    year = 2023,
    publisher = "ACM",
    address = "New York, NY, USA",
    series = "SatCom '23",
    location = "Madrid, Spain",
    doi = "10.1145/3570361.3614239"
}
```

A preprint is available on [arXiv](https://arxiv.org/abs/2306.09756).
For a full list of publications, please see [our website](https://www.tu.berlin/en/mcc/research/publications).

## License

All code in this repository is licensed under the terms of the [GNU General Public License Version 3](./LICENSE), the same as the original repository.
The Mars surface texture is provided by [Solar System Scope](https://www.solarsystemscope.com/textures/) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
Pointer to this resource and code for using surface textures in VTK adapted from [souwang324/solarStars](https://github.com/souwang324/solarStars).
Locations of Mars landing sites in `site_data.txt` from [The Planetary Society](https://www.planetary.org/space-images/mars_landing_site_map_lakdawalla).

## Installation

This code requires Python and a desktop environment to spawn the GUI.
We have tested this code with Python 3.9.
Install the requirements with `pip`:

```sh
python3.9 pip install -r requirements.txt
```

## Run

Run the GUI with `python3 gui.py`.
