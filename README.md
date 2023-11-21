# Compute travel time matrices

This is a Python package to handle the high-level logic of computing travel time
matrices for multiple travel modes using [`r5py`](https://r5py.readthedocs.io/).

This package is used, for instance, for [calculating travel time matrices of the
Helsinki metropolitan
area](https://github.com/DigitalGeographyLab/Helsinki-Travel-Time-Matrices).


## Use

Create a `data` directory, within that a config file according to the template
provided in `travel_time_matrix_computer.yml.example`, and pass it to `python
-m travel_time_matrix_computer`


## Dependencies

This package dependes on
[car_speed_annotator](https://github.com/DigitalGeographyLab/car-speed-annotator), 
[cycling_speed_annotator](https://github.com/DigitalGeographyLab/car-speed-annotator), and
[parking_times_calculator](https://github.com/DigitalGeographyLab/car-speed-annotator), as well as all dependencies listed there.
