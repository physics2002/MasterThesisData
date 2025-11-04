# MasterThesisData

Measurement Data:

File format is ROOT with 4 columns: timestamp (in ns), β-detector energy (in channels), γ-detector energy (in channels) and a detector ID indicating whether the event is from the β-
or γ-detector.

File names follow the convention: Sample_Mass_MMeasTime_AActTime_betaIDx_gammaIDy.root

where Sample is the sample name, Mass is the sample mass in grams, MeasTime is the measurement time, ActTime is the activation time, and x, y are the identication
numbers of the β- and γ-detectors used in the measurement, respectively.

Simulation Data:

All files have 3 columns, 1st column: neutron energy (eV), 2nd column: spectral uence (cm^{-2}eV^{-1}) and 3rd column: statistical spectral uence uncertainty (cm^{-2}eV^{-1}).
