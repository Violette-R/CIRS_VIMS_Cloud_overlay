# Overlay of CASSINI/CIRS FP1 & FP4 satellite observation on VIMS polar projections with spectral color to highlight the clouds on Titan.

This contains a Jupyter Notebook developed during a Master 2 research internship. The goal is to investigate a potential cloud overlap with Cassini/CIRS observations on the North Pole of Titan. Cassini is a satellite orbiter that observed Titan from 2004 to 2017 (date to be verified). CIRS is a Composite Infrared Spectrometer and VIMS is a Visual and Infrared Spectrometer. The footprints of CIRS instrument observations for focal FP1 and focal FP4 are overlaid on a background of:
- a recomposed Radar polar projection, to highlight Titan's lakes and seas. (NASA/JPL-Caltech/ASI/USGS)
- a VIMS cube, with false-color based on Brown et al. (2010), to highlight the troposphere and thus the methane clouds at the chosen date.

This overlay allows to estimate whether the CIRS measurements might have intersected atmospheric methane clouds. The VIMS cube needs to be selected on the closest date possible to the CIRS observation. Since the CIRS and VIMS did not operate simultaneously, the visual comparison provides a global idea, a qualitative insight, into potential cloud signal in the selected CIRS data.

The FP1 has a focal opening of 3.9 mrad, while the FP4 has a focal opening of 0.27 mrad (Jennings et al., 2017). The FP4 consists of a rectangular array of detectors, but in this visualization, each detector is represented by a circle.

The VIMS data are available on the Cassini VIMS Data Portal (https://vims.univ-nantes.fr/).

The CIRS data were selected using the Read Vanilla widget, developed by Thierry Fouchet.

## Repository Contents

- `Overlay_Cloud_CIRS_VIMS_on_Titan.ipynb`: Main notebook with the visual overlay and analysis.
- `requirements.txt`: Python dependencies required to run the notebook.
- `Titan_Radar.jpg`: Radar polar projection used as a background, from NASA.
- `data/`: Directory to place external data files such as VIMS cubes or CIRS observations. Contains example data.

## Usage Instructions

1. Download the folder.  
2. Run `pip install -r requirements.txt`  
3. Open the notebook, with VS Code, Jupyter Notebook, or alternatives (`jupyter notebook Overlay_Cloud_CIRS_VIMS_on_Titan.ipynb`)

## Author

Violette Renneville  
Master 2 Research Internship  
Laboratory: Observatoire de Paris  
Contact: renneville.v@gmail.com
