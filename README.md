# Swarming intelligence emergence underlying monocyte communication and activation in cellular immunity 
------

## Introduction
Code for manuscript " Swarming intelligence emergence underlying monocyte communication and activation in cellular immunity ".

------
## Dataset
To uncover the molecular basis that modulates the pattern of monocyte migration, we collected comprehensive data of the monocyte migration through intravital imaging under different experiments. Here, we only upload the demo dataset with our code for validation and investigation. The complete monocyte migration dataset is available after contact the corresponding authors on reasonable request.

------
## Usage
### Classification and Simulation
``classifier.py`` provides cell contact classifiers.
``Cell_simulation`` generates cell motion simulation trajectories.
The data used to train the cell contact classifier and the classification model are in ``/data``
### Calcium ion analysis
``distance_distribution.py`` provides statistics of cell distances.
``generate_contact_data_csv.py`` generates data on contact cells.
``generate_spike_data_csv.py`` generates data on calcium spikes.
``generate_peak_contact.py`` generates contact data for cells with calcium spikes.
