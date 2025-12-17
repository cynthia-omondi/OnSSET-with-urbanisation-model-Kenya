ONSSET : Open Source Spatial Electrification Tool with spatial changes in urbanisation
=================================================

## Overview

This repository contains the source code for OnSSET extended with a binomial logistic regression model to project spatial and temporal changes in urbanisation in Kenya.

The regression model is used to estimate the probability of urbanisation at the spatial level, enabling improved representation of urban growth dynamics within the OnSSET framework.

## Repository Structure

- ### OnSSET CODE/
  Contains the core OnSSET model source code used for energy access and electrification analysis.

- ### urbanisation_code.m
  MATLAB implementation of the binomial logistic regression model used to generate urbanisation projections.

- ### urbanisation_code.py
  Python implementation of the same regression model, provided as an alternative to the MATLAB version.

## Notes

Both the MATLAB and Python scripts perform equivalent functionality and can be used interchangeably depending on user preference.

The outputs of the regression model are intended to be integrated into the OnSSET workflow to inform urban–rural classification and scenario analysis

## Contact
For more information regarding the urbanisation model, its functionality and implementation
please contact the author at dorcus70@gmail.com
