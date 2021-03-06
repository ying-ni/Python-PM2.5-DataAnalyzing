=== Run information ===

Scheme:       weka.classifiers.trees.RandomTree -K 0 -M 1.0 -V 0.001 -S 1
Relation:     KH-1982-2018
Instances:    401
Attributes:   13
              SO2
              CO
              O3
              PM25
              Nox
              NO
              NO2
              THC
              NMHC
              CH4
              WindSpeed
              TEMP
              Humidity
Test mode:    evaluate on training data

=== Classifier model (full training set) ===


RandomTree
==========

THC < 2.12
|   CO < 0.42
|   |   THC < 2
|   |   |   NO < 3.77
|   |   |   |   O3 < 29.15
|   |   |   |   |   NO < 3.49
|   |   |   |   |   |   TEMP < 29.3
|   |   |   |   |   |   |   TEMP < 28.88
|   |   |   |   |   |   |   |   SO2 < 3.25
|   |   |   |   |   |   |   |   |   SO2 < 2.55 : 10 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 2.55 : 9 (1/0)
|   |   |   |   |   |   |   |   SO2 >= 3.25 : 11 (1/0)
|   |   |   |   |   |   |   TEMP >= 28.88
|   |   |   |   |   |   |   |   Humidity < 78.71
|   |   |   |   |   |   |   |   |   O3 < 24.7
|   |   |   |   |   |   |   |   |   |   NO2 < 9.25 : 14 (1/0)
|   |   |   |   |   |   |   |   |   |   NO2 >= 9.25
|   |   |   |   |   |   |   |   |   |   |   NO < 2.94
|   |   |   |   |   |   |   |   |   |   |   |   O3 < 23.05 : 12 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   O3 >= 23.05 : 11 (1/0)
|   |   |   |   |   |   |   |   |   |   |   NO >= 2.94 : 13 (1/0)
|   |   |   |   |   |   |   |   |   O3 >= 24.7
|   |   |   |   |   |   |   |   |   |   NO < 2.12 : 13 (2/0)
|   |   |   |   |   |   |   |   |   |   NO >= 2.12
|   |   |   |   |   |   |   |   |   |   |   O3 < 25.85 : 14 (1/0)
|   |   |   |   |   |   |   |   |   |   |   O3 >= 25.85 : 15 (2/0)
|   |   |   |   |   |   |   |   Humidity >= 78.71
|   |   |   |   |   |   |   |   |   SO2 < 2.1 : 11 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 2.1 : 12 (2/0)
|   |   |   |   |   |   TEMP >= 29.3
|   |   |   |   |   |   |   NO < 3.08
|   |   |   |   |   |   |   |   WindSpeed < 2.6
|   |   |   |   |   |   |   |   |   Nox < 11.79
|   |   |   |   |   |   |   |   |   |   TEMP < 29.52
|   |   |   |   |   |   |   |   |   |   |   Nox < 8.8 : 8 (1/0)
|   |   |   |   |   |   |   |   |   |   |   Nox >= 8.8 : 7 (1/0)
|   |   |   |   |   |   |   |   |   |   TEMP >= 29.52
|   |   |   |   |   |   |   |   |   |   |   O3 < 23.35
|   |   |   |   |   |   |   |   |   |   |   |   SO2 < 3 : 9 (2/0)
|   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 3
|   |   |   |   |   |   |   |   |   |   |   |   |   NO2 < 7.5 : 10 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   NO2 >= 7.5 : 9 (1/0)
|   |   |   |   |   |   |   |   |   |   |   O3 >= 23.35 : 11 (1/0)
|   |   |   |   |   |   |   |   |   Nox >= 11.79
|   |   |   |   |   |   |   |   |   |   NMHC < 0.11
|   |   |   |   |   |   |   |   |   |   |   TEMP < 29.45
|   |   |   |   |   |   |   |   |   |   |   |   SO2 < 4.6 : 12 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 4.6 : 8 (1/0)
|   |   |   |   |   |   |   |   |   |   |   TEMP >= 29.45
|   |   |   |   |   |   |   |   |   |   |   |   THC < 1.94
|   |   |   |   |   |   |   |   |   |   |   |   |   O3 < 22.6
|   |   |   |   |   |   |   |   |   |   |   |   |   |   TEMP < 30.39 : 12 (3/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   TEMP >= 30.39 : 13 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   O3 >= 22.6 : 11 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   THC >= 1.94
|   |   |   |   |   |   |   |   |   |   |   |   |   Nox < 14.55 : 13 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   Nox >= 14.55 : 14 (1/0)
|   |   |   |   |   |   |   |   |   |   NMHC >= 0.11
|   |   |   |   |   |   |   |   |   |   |   O3 < 24.45
|   |   |   |   |   |   |   |   |   |   |   |   SO2 < 2.8 : 10 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 2.8 : 9 (1/0)
|   |   |   |   |   |   |   |   |   |   |   O3 >= 24.45 : 8 (1/0)
|   |   |   |   |   |   |   |   WindSpeed >= 2.6
|   |   |   |   |   |   |   |   |   CO < 0.15
|   |   |   |   |   |   |   |   |   |   O3 < 23.05 : 13 (1/0)
|   |   |   |   |   |   |   |   |   |   O3 >= 23.05 : 12 (1/0)
|   |   |   |   |   |   |   |   |   CO >= 0.15 : 14 (1/0)
|   |   |   |   |   |   |   NO >= 3.08
|   |   |   |   |   |   |   |   SO2 < 3.95 : 7 (2/0)
|   |   |   |   |   |   |   |   SO2 >= 3.95
|   |   |   |   |   |   |   |   |   SO2 < 4.3 : 8 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 4.3 : 9 (1/0)
|   |   |   |   |   NO >= 3.49
|   |   |   |   |   |   O3 < 24.35
|   |   |   |   |   |   |   NMHC < 0.13
|   |   |   |   |   |   |   |   Nox < 14.16 : 9 (1/0)
|   |   |   |   |   |   |   |   Nox >= 14.16 : 11 (1/0)
|   |   |   |   |   |   |   NMHC >= 0.13
|   |   |   |   |   |   |   |   SO2 < 3.15 : 14 (2/0)
|   |   |   |   |   |   |   |   SO2 >= 3.15
|   |   |   |   |   |   |   |   |   CO < 0.29 : 15 (1/0)
|   |   |   |   |   |   |   |   |   CO >= 0.29 : 14 (1/0)
|   |   |   |   |   |   O3 >= 24.35
|   |   |   |   |   |   |   CO < 0.32 : 17 (1/0)
|   |   |   |   |   |   |   CO >= 0.32
|   |   |   |   |   |   |   |   O3 < 26.9 : 19 (1/0)
|   |   |   |   |   |   |   |   O3 >= 26.9 : 21 (1/0)
|   |   |   |   O3 >= 29.15
|   |   |   |   |   Nox < 7.05 : 13 (2/0)
|   |   |   |   |   Nox >= 7.05
|   |   |   |   |   |   TEMP < 27.52
|   |   |   |   |   |   |   SO2 < 5.15 : 23 (1/0)
|   |   |   |   |   |   |   SO2 >= 5.15 : 21 (1/0)
|   |   |   |   |   |   TEMP >= 27.52
|   |   |   |   |   |   |   WindSpeed < 2.24
|   |   |   |   |   |   |   |   THC < 1.97
|   |   |   |   |   |   |   |   |   CO < 0.38
|   |   |   |   |   |   |   |   |   |   THC < 1.96 : 17 (2/0)
|   |   |   |   |   |   |   |   |   |   THC >= 1.96 : 16 (2/0)
|   |   |   |   |   |   |   |   |   CO >= 0.38 : 14 (1/0)
|   |   |   |   |   |   |   |   THC >= 1.97
|   |   |   |   |   |   |   |   |   SO2 < 4.1 : 18 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 4.1 : 19 (1/0)
|   |   |   |   |   |   |   WindSpeed >= 2.24
|   |   |   |   |   |   |   |   NO < 2.69
|   |   |   |   |   |   |   |   |   Nox < 9.88 : 17 (1/0)
|   |   |   |   |   |   |   |   |   Nox >= 9.88
|   |   |   |   |   |   |   |   |   |   CO < 0.33 : 20 (1/0)
|   |   |   |   |   |   |   |   |   |   CO >= 0.33 : 19 (3/0)
|   |   |   |   |   |   |   |   NO >= 2.69 : 22 (1/0)
|   |   |   NO >= 3.77
|   |   |   |   Humidity < 74.54
|   |   |   |   |   O3 < 17.35
|   |   |   |   |   |   CO < 0.27
|   |   |   |   |   |   |   O3 < 14.95 : 9 (2/0)
|   |   |   |   |   |   |   O3 >= 14.95
|   |   |   |   |   |   |   |   CO < 0.23 : 3 (1/0)
|   |   |   |   |   |   |   |   CO >= 0.23 : 6 (1/0)
|   |   |   |   |   |   CO >= 0.27
|   |   |   |   |   |   |   CO < 0.29 : 11 (1/0)
|   |   |   |   |   |   |   CO >= 0.29
|   |   |   |   |   |   |   |   SO2 < 4.25 : 9 (1/0)
|   |   |   |   |   |   |   |   SO2 >= 4.25 : 10 (1/0)
|   |   |   |   |   O3 >= 17.35
|   |   |   |   |   |   Humidity < 74.06
|   |   |   |   |   |   |   Nox < 17.91
|   |   |   |   |   |   |   |   Nox < 17.48
|   |   |   |   |   |   |   |   |   O3 < 22.05 : 12 (3/0)
|   |   |   |   |   |   |   |   |   O3 >= 22.05
|   |   |   |   |   |   |   |   |   |   O3 < 25.05 : 13 (1/0)
|   |   |   |   |   |   |   |   |   |   O3 >= 25.05 : 12 (1/0)
|   |   |   |   |   |   |   |   Nox >= 17.48 : 11 (1/0)
|   |   |   |   |   |   |   Nox >= 17.91 : 14 (1/0)
|   |   |   |   |   |   Humidity >= 74.06 : 16 (1/0)
|   |   |   |   Humidity >= 74.54
|   |   |   |   |   O3 < 20.95
|   |   |   |   |   |   NMHC < 0.18
|   |   |   |   |   |   |   NO2 < 13.09
|   |   |   |   |   |   |   |   CH4 < 1.78
|   |   |   |   |   |   |   |   |   NO2 < 11 : 9 (1/0)
|   |   |   |   |   |   |   |   |   NO2 >= 11 : 8 (2/0)
|   |   |   |   |   |   |   |   CH4 >= 1.78
|   |   |   |   |   |   |   |   |   Nox < 17.24
|   |   |   |   |   |   |   |   |   |   CO < 0.3 : 7 (1/0)
|   |   |   |   |   |   |   |   |   |   CO >= 0.3 : 8 (1/0)
|   |   |   |   |   |   |   |   |   Nox >= 17.24
|   |   |   |   |   |   |   |   |   |   CO < 0.24 : 7 (1/0)
|   |   |   |   |   |   |   |   |   |   CO >= 0.24 : 6 (2/0)
|   |   |   |   |   |   |   NO2 >= 13.09
|   |   |   |   |   |   |   |   CH4 < 1.81 : 9 (2/0)
|   |   |   |   |   |   |   |   CH4 >= 1.81
|   |   |   |   |   |   |   |   |   Nox < 18.19 : 9 (1/0)
|   |   |   |   |   |   |   |   |   Nox >= 18.19 : 8 (2/0)
|   |   |   |   |   |   NMHC >= 0.18 : 10 (1/0)
|   |   |   |   |   O3 >= 20.95
|   |   |   |   |   |   CH4 < 1.77 : 13 (1/0)
|   |   |   |   |   |   CH4 >= 1.77
|   |   |   |   |   |   |   Nox < 16.28 : 12 (1/0)
|   |   |   |   |   |   |   Nox >= 16.28
|   |   |   |   |   |   |   |   Nox < 18.8 : 9 (2/0)
|   |   |   |   |   |   |   |   Nox >= 18.8 : 11 (1/0)
|   |   THC >= 2
|   |   |   O3 < 28.15
|   |   |   |   NMHC < 0.15
|   |   |   |   |   WindSpeed < 1.79
|   |   |   |   |   |   SO2 < 3.5
|   |   |   |   |   |   |   Nox < 12.43 : 11 (1/0)
|   |   |   |   |   |   |   Nox >= 12.43 : 8 (1/0)
|   |   |   |   |   |   SO2 >= 3.5 : 15 (1/0)
|   |   |   |   |   WindSpeed >= 1.79
|   |   |   |   |   |   Humidity < 74.6
|   |   |   |   |   |   |   CO < 0.32 : 13 (1/0)
|   |   |   |   |   |   |   CO >= 0.32 : 12 (2/0)
|   |   |   |   |   |   Humidity >= 74.6
|   |   |   |   |   |   |   O3 < 23.1
|   |   |   |   |   |   |   |   SO2 < 3.35
|   |   |   |   |   |   |   |   |   SO2 < 3.2 : 14 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 3.2 : 15 (1/0)
|   |   |   |   |   |   |   |   SO2 >= 3.35 : 11 (1/0)
|   |   |   |   |   |   |   O3 >= 23.1
|   |   |   |   |   |   |   |   SO2 < 3.5
|   |   |   |   |   |   |   |   |   SO2 < 3.25 : 13 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 3.25 : 14 (1/0)
|   |   |   |   |   |   |   |   SO2 >= 3.5
|   |   |   |   |   |   |   |   |   Nox < 20.1
|   |   |   |   |   |   |   |   |   |   SO2 < 5.05 : 16 (2/0)
|   |   |   |   |   |   |   |   |   |   SO2 >= 5.05 : 15 (1/0)
|   |   |   |   |   |   |   |   |   Nox >= 20.1 : 15 (2/0)
|   |   |   |   NMHC >= 0.15
|   |   |   |   |   NO < 5.27
|   |   |   |   |   |   Nox < 15.39
|   |   |   |   |   |   |   O3 < 22.95
|   |   |   |   |   |   |   |   NO2 < 11.7
|   |   |   |   |   |   |   |   |   NO2 < 11.33
|   |   |   |   |   |   |   |   |   |   NMHC < 0.15 : 9 (1/0)
|   |   |   |   |   |   |   |   |   |   NMHC >= 0.15
|   |   |   |   |   |   |   |   |   |   |   O3 < 15.45 : 7 (1/0)
|   |   |   |   |   |   |   |   |   |   |   O3 >= 15.45 : 8 (2/0)
|   |   |   |   |   |   |   |   |   NO2 >= 11.33 : 11 (1/0)
|   |   |   |   |   |   |   |   NO2 >= 11.7 : 7 (1/0)
|   |   |   |   |   |   |   O3 >= 22.95 : 11 (1/0)
|   |   |   |   |   |   Nox >= 15.39
|   |   |   |   |   |   |   O3 < 14.05 : 15 (1/0)
|   |   |   |   |   |   |   O3 >= 14.05
|   |   |   |   |   |   |   |   Nox < 18.83 : 12 (1/0)
|   |   |   |   |   |   |   |   Nox >= 18.83 : 11 (1/0)
|   |   |   |   |   NO >= 5.27 : 16 (1/0)
|   |   |   O3 >= 28.15
|   |   |   |   TEMP < 28.43
|   |   |   |   |   TEMP < 25.9
|   |   |   |   |   |   SO2 < 3.6
|   |   |   |   |   |   |   CO < 0.4 : 28 (2/0)
|   |   |   |   |   |   |   CO >= 0.4 : 29 (1/0)
|   |   |   |   |   |   SO2 >= 3.6
|   |   |   |   |   |   |   NO < 1.84 : 21 (1/0)
|   |   |   |   |   |   |   NO >= 1.84
|   |   |   |   |   |   |   |   Nox < 17.13
|   |   |   |   |   |   |   |   |   Nox < 15.38 : 25 (1/0)
|   |   |   |   |   |   |   |   |   Nox >= 15.38 : 24 (1/0)
|   |   |   |   |   |   |   |   Nox >= 17.13 : 23 (2/0)
|   |   |   |   |   TEMP >= 25.9
|   |   |   |   |   |   NMHC < 0.04 : 29 (1/0)
|   |   |   |   |   |   NMHC >= 0.04
|   |   |   |   |   |   |   Nox < 9.61 : 18 (1/0)
|   |   |   |   |   |   |   Nox >= 9.61
|   |   |   |   |   |   |   |   Nox < 20.59
|   |   |   |   |   |   |   |   |   NMHC < 0.13
|   |   |   |   |   |   |   |   |   |   O3 < 33.25
|   |   |   |   |   |   |   |   |   |   |   SO2 < 3.85 : 20 (1/0)
|   |   |   |   |   |   |   |   |   |   |   SO2 >= 3.85 : 19 (1/0)
|   |   |   |   |   |   |   |   |   |   O3 >= 33.25
|   |   |   |   |   |   |   |   |   |   |   CO < 0.35
|   |   |   |   |   |   |   |   |   |   |   |   TEMP < 26.04 : 22 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   TEMP >= 26.04 : 21 (3/0)
|   |   |   |   |   |   |   |   |   |   |   CO >= 0.35
|   |   |   |   |   |   |   |   |   |   |   |   CO < 0.37 : 23 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   CO >= 0.37 : 24 (1/0)
|   |   |   |   |   |   |   |   |   NMHC >= 0.13
|   |   |   |   |   |   |   |   |   |   NO2 < 15.2 : 25 (2/0)
|   |   |   |   |   |   |   |   |   |   NO2 >= 15.2
|   |   |   |   |   |   |   |   |   |   |   NO < 2.93 : 23 (1/0)
|   |   |   |   |   |   |   |   |   |   |   NO >= 2.93 : 24 (1/0)
|   |   |   |   |   |   |   |   Nox >= 20.59 : 18 (1/0)
|   |   |   |   TEMP >= 28.43
|   |   |   |   |   CO < 0.39
|   |   |   |   |   |   NO < 2.2
|   |   |   |   |   |   |   SO2 < 3.8
|   |   |   |   |   |   |   |   Humidity < 78.87
|   |   |   |   |   |   |   |   |   TEMP < 28.54 : 17 (1/0)
|   |   |   |   |   |   |   |   |   TEMP >= 28.54 : 16 (3/0)
|   |   |   |   |   |   |   |   Humidity >= 78.87 : 13 (1/0)
|   |   |   |   |   |   |   SO2 >= 3.8
|   |   |   |   |   |   |   |   Nox < 10.93 : 21 (1/0)
|   |   |   |   |   |   |   |   Nox >= 10.93 : 20 (2/0)
|   |   |   |   |   |   NO >= 2.2
|   |   |   |   |   |   |   CO < 0.33
|   |   |   |   |   |   |   |   Nox < 14.56 : 22 (2/0)
|   |   |   |   |   |   |   |   Nox >= 14.56 : 21 (2/0)
|   |   |   |   |   |   |   CO >= 0.33 : 19 (3/0)
|   |   |   |   |   CO >= 0.39
|   |   |   |   |   |   NO2 < 12.59 : 15 (1/0)
|   |   |   |   |   |   NO2 >= 12.59 : 16 (2/0)
|   CO >= 0.42
|   |   SO2 < 3.25
|   |   |   Nox < 22.3
|   |   |   |   SO2 < 2.9 : 37 (1/0)
|   |   |   |   SO2 >= 2.9 : 33 (1/0)
|   |   |   Nox >= 22.3 : 47 (1/0)
|   |   SO2 >= 3.25
|   |   |   TEMP < 27.78
|   |   |   |   SO2 < 6.1
|   |   |   |   |   THC < 2.05
|   |   |   |   |   |   Nox < 19.01 : 25 (1/0)
|   |   |   |   |   |   Nox >= 19.01
|   |   |   |   |   |   |   SO2 < 4.65 : 22 (1/0)
|   |   |   |   |   |   |   SO2 >= 4.65 : 21 (2/0)
|   |   |   |   |   THC >= 2.05
|   |   |   |   |   |   NMHC < 0.15
|   |   |   |   |   |   |   SO2 < 4.35
|   |   |   |   |   |   |   |   SO2 < 3.65 : 28 (1/0)
|   |   |   |   |   |   |   |   SO2 >= 3.65
|   |   |   |   |   |   |   |   |   O3 < 45.25 : 31 (1/0)
|   |   |   |   |   |   |   |   |   O3 >= 45.25 : 30 (1/0)
|   |   |   |   |   |   |   SO2 >= 4.35 : 26 (1/0)
|   |   |   |   |   |   NMHC >= 0.15
|   |   |   |   |   |   |   NO2 < 14.36
|   |   |   |   |   |   |   |   CO < 0.45 : 27 (1/0)
|   |   |   |   |   |   |   |   CO >= 0.45 : 29 (1/0)
|   |   |   |   |   |   |   NO2 >= 14.36 : 24 (2/0)
|   |   |   |   SO2 >= 6.1
|   |   |   |   |   NO < 3.6 : 32 (1/0)
|   |   |   |   |   NO >= 3.6 : 31 (1/0)
|   |   |   TEMP >= 27.78
|   |   |   |   NO < 3.4
|   |   |   |   |   SO2 < 4.55
|   |   |   |   |   |   NO < 2.33 : 20 (1/0)
|   |   |   |   |   |   NO >= 2.33
|   |   |   |   |   |   |   SO2 < 4.05 : 16 (1/0)
|   |   |   |   |   |   |   SO2 >= 4.05 : 17 (1/0)
|   |   |   |   |   SO2 >= 4.55
|   |   |   |   |   |   SO2 < 5.15 : 29 (1/0)
|   |   |   |   |   |   SO2 >= 5.15 : 20 (1/0)
|   |   |   |   NO >= 3.4
|   |   |   |   |   NO < 4.58
|   |   |   |   |   |   NO < 3.65
|   |   |   |   |   |   |   SO2 < 4.45 : 11 (1/0)
|   |   |   |   |   |   |   SO2 >= 4.45
|   |   |   |   |   |   |   |   SO2 < 5.6 : 13 (1/0)
|   |   |   |   |   |   |   |   SO2 >= 5.6 : 14 (1/0)
|   |   |   |   |   |   NO >= 3.65
|   |   |   |   |   |   |   NO < 3.92 : 19 (1/0)
|   |   |   |   |   |   |   NO >= 3.92
|   |   |   |   |   |   |   |   O3 < 28.3 : 15 (1/0)
|   |   |   |   |   |   |   |   O3 >= 28.3 : 16 (1/0)
|   |   |   |   |   NO >= 4.58
|   |   |   |   |   |   SO2 < 4.3
|   |   |   |   |   |   |   CO < 0.47 : 8 (2/0)
|   |   |   |   |   |   |   CO >= 0.47 : 6 (1/0)
|   |   |   |   |   |   SO2 >= 4.3 : 14 (1/0)
THC >= 2.12
|   NO2 < 15.28
|   |   TEMP < 27.93
|   |   |   NMHC < 0.14
|   |   |   |   O3 < 44.85
|   |   |   |   |   CO < 0.3 : 24 (1/0)
|   |   |   |   |   CO >= 0.3
|   |   |   |   |   |   WindSpeed < 2.32 : 27 (2/0)
|   |   |   |   |   |   WindSpeed >= 2.32 : 25 (1/0)
|   |   |   |   O3 >= 44.85
|   |   |   |   |   CO < 0.42
|   |   |   |   |   |   SO2 < 4 : 30 (1/0)
|   |   |   |   |   |   SO2 >= 4 : 29 (1/0)
|   |   |   |   |   CO >= 0.42 : 32 (1/0)
|   |   |   NMHC >= 0.14
|   |   |   |   SO2 < 4.45 : 18 (1/0)
|   |   |   |   SO2 >= 4.45
|   |   |   |   |   O3 < 30.75 : 24 (2/0)
|   |   |   |   |   O3 >= 30.75 : 23 (1/0)
|   |   TEMP >= 27.93
|   |   |   NO < 3.47
|   |   |   |   CO < 0.26
|   |   |   |   |   CH4 < 2.02
|   |   |   |   |   |   O3 < 21.45 : 13 (1/0)
|   |   |   |   |   |   O3 >= 21.45 : 12 (1/0)
|   |   |   |   |   CH4 >= 2.02
|   |   |   |   |   |   O3 < 20 : 16 (1/0)
|   |   |   |   |   |   O3 >= 20 : 19 (1/0)
|   |   |   |   CO >= 0.26
|   |   |   |   |   CH4 < 2.08
|   |   |   |   |   |   NO2 < 14.11
|   |   |   |   |   |   |   CO < 0.41
|   |   |   |   |   |   |   |   Nox < 13.32 : 17 (1/0)
|   |   |   |   |   |   |   |   Nox >= 13.32
|   |   |   |   |   |   |   |   |   THC < 2.2 : 15 (1/0)
|   |   |   |   |   |   |   |   |   THC >= 2.2 : 16 (2/0)
|   |   |   |   |   |   |   CO >= 0.41 : 18 (1/0)
|   |   |   |   |   |   NO2 >= 14.11
|   |   |   |   |   |   |   Nox < 18.23 : 22 (1/0)
|   |   |   |   |   |   |   Nox >= 18.23 : 19 (1/0)
|   |   |   |   |   CH4 >= 2.08
|   |   |   |   |   |   CO < 0.27 : 23 (1/0)
|   |   |   |   |   |   CO >= 0.27
|   |   |   |   |   |   |   SO2 < 3.8 : 21 (1/0)
|   |   |   |   |   |   |   SO2 >= 3.8 : 20 (1/0)
|   |   |   NO >= 3.47
|   |   |   |   Nox < 13.32 : 8 (1/0)
|   |   |   |   Nox >= 13.32
|   |   |   |   |   CO < 0.38 : 14 (1/0)
|   |   |   |   |   CO >= 0.38 : 12 (1/0)
|   NO2 >= 15.28
|   |   Nox < 22.05
|   |   |   NMHC < 0.2
|   |   |   |   THC < 2.17
|   |   |   |   |   SO2 < 3.2
|   |   |   |   |   |   NO < 4.83
|   |   |   |   |   |   |   NO2 < 15.82 : 38 (1/0)
|   |   |   |   |   |   |   NO2 >= 15.82 : 41 (1/0)
|   |   |   |   |   |   NO >= 4.83 : 34 (1/0)
|   |   |   |   |   SO2 >= 3.2
|   |   |   |   |   |   NO2 < 18.02
|   |   |   |   |   |   |   Nox < 18.14 : 34 (1/0)
|   |   |   |   |   |   |   Nox >= 18.14
|   |   |   |   |   |   |   |   O3 < 31.15
|   |   |   |   |   |   |   |   |   SO2 < 4.25 : 28 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 4.25 : 26 (2/0)
|   |   |   |   |   |   |   |   O3 >= 31.15
|   |   |   |   |   |   |   |   |   CO < 0.43
|   |   |   |   |   |   |   |   |   |   O3 < 39.85 : 29 (2/0)
|   |   |   |   |   |   |   |   |   |   O3 >= 39.85 : 27 (1/0)
|   |   |   |   |   |   |   |   |   CO >= 0.43
|   |   |   |   |   |   |   |   |   |   Nox < 19.72 : 31 (1/0)
|   |   |   |   |   |   |   |   |   |   Nox >= 19.72
|   |   |   |   |   |   |   |   |   |   |   NO < 2.49 : 32 (2/0)
|   |   |   |   |   |   |   |   |   |   |   NO >= 2.49 : 31 (1/0)
|   |   |   |   |   |   NO2 >= 18.02 : 37 (1/0)
|   |   |   |   THC >= 2.17
|   |   |   |   |   CO < 0.39 : 29 (1/0)
|   |   |   |   |   CO >= 0.39
|   |   |   |   |   |   WindSpeed < 1.94
|   |   |   |   |   |   |   Humidity < 65 : 33 (1/0)
|   |   |   |   |   |   |   Humidity >= 65 : 35 (3/0)
|   |   |   |   |   |   WindSpeed >= 1.94
|   |   |   |   |   |   |   Nox < 20.13 : 40 (3/0)
|   |   |   |   |   |   |   Nox >= 20.13
|   |   |   |   |   |   |   |   SO2 < 6.35
|   |   |   |   |   |   |   |   |   SO2 < 3.75 : 40 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 3.75
|   |   |   |   |   |   |   |   |   |   O3 < 39.7 : 36 (1/0)
|   |   |   |   |   |   |   |   |   |   O3 >= 39.7 : 38 (1/0)
|   |   |   |   |   |   |   |   SO2 >= 6.35 : 32 (1/0)
|   |   |   NMHC >= 0.2
|   |   |   |   O3 < 36.85
|   |   |   |   |   SO2 < 4.65
|   |   |   |   |   |   NMHC < 0.21 : 27 (1/0)
|   |   |   |   |   |   NMHC >= 0.21
|   |   |   |   |   |   |   Nox < 20.83 : 26 (1/0)
|   |   |   |   |   |   |   Nox >= 20.83 : 25 (1/0)
|   |   |   |   |   SO2 >= 4.65 : 28 (1/0)
|   |   |   |   O3 >= 36.85
|   |   |   |   |   SO2 < 3.95 : 30 (1/0)
|   |   |   |   |   SO2 >= 3.95 : 28 (3/0)
|   |   Nox >= 22.05
|   |   |   O3 < 32.45
|   |   |   |   CH4 < 1.92
|   |   |   |   |   Nox < 27.38 : 23 (1/0)
|   |   |   |   |   Nox >= 27.38 : 26 (1/0)
|   |   |   |   CH4 >= 1.92
|   |   |   |   |   Humidity < 74.5
|   |   |   |   |   |   CO < 0.55
|   |   |   |   |   |   |   CH4 < 2.08
|   |   |   |   |   |   |   |   Nox < 25.36
|   |   |   |   |   |   |   |   |   CO < 0.54
|   |   |   |   |   |   |   |   |   |   NO < 2.41 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   NO >= 2.41
|   |   |   |   |   |   |   |   |   |   |   NO < 4.28
|   |   |   |   |   |   |   |   |   |   |   |   SO2 < 2.95 : 42 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 2.95 : 43 (2/0)
|   |   |   |   |   |   |   |   |   |   |   NO >= 4.28 : 44 (1/0)
|   |   |   |   |   |   |   |   |   CO >= 0.54 : 40 (1/0)
|   |   |   |   |   |   |   |   Nox >= 25.36
|   |   |   |   |   |   |   |   |   NO2 < 23.38
|   |   |   |   |   |   |   |   |   |   Nox < 26.74
|   |   |   |   |   |   |   |   |   |   |   NO < 4.04 : 35 (1/0)
|   |   |   |   |   |   |   |   |   |   |   NO >= 4.04 : 36 (2/0)
|   |   |   |   |   |   |   |   |   |   Nox >= 26.74
|   |   |   |   |   |   |   |   |   |   |   NO2 < 21.96 : 42 (1/0)
|   |   |   |   |   |   |   |   |   |   |   NO2 >= 21.96
|   |   |   |   |   |   |   |   |   |   |   |   O3 < 27.2 : 39 (2/0)
|   |   |   |   |   |   |   |   |   |   |   |   O3 >= 27.2
|   |   |   |   |   |   |   |   |   |   |   |   |   THC < 2.27 : 38 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   THC >= 2.27 : 37 (1/0)
|   |   |   |   |   |   |   |   |   NO2 >= 23.38
|   |   |   |   |   |   |   |   |   |   Nox < 29.14 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   Nox >= 29.14 : 43 (1/0)
|   |   |   |   |   |   |   CH4 >= 2.08
|   |   |   |   |   |   |   |   O3 < 28.85
|   |   |   |   |   |   |   |   |   O3 < 26.7
|   |   |   |   |   |   |   |   |   |   NO < 3.66 : 38 (1/0)
|   |   |   |   |   |   |   |   |   |   NO >= 3.66
|   |   |   |   |   |   |   |   |   |   |   O3 < 24.8 : 40 (1/0)
|   |   |   |   |   |   |   |   |   |   |   O3 >= 24.8 : 39 (1/0)
|   |   |   |   |   |   |   |   |   O3 >= 26.7
|   |   |   |   |   |   |   |   |   |   SO2 < 5.2 : 35 (1/0)
|   |   |   |   |   |   |   |   |   |   SO2 >= 5.2 : 36 (1/0)
|   |   |   |   |   |   |   |   O3 >= 28.85 : 26 (1/0)
|   |   |   |   |   |   CO >= 0.55
|   |   |   |   |   |   |   NO < 2.83
|   |   |   |   |   |   |   |   Nox < 25.02 : 45 (1/0)
|   |   |   |   |   |   |   |   Nox >= 25.02 : 49 (1/0)
|   |   |   |   |   |   |   NO >= 2.83
|   |   |   |   |   |   |   |   SO2 < 6.35
|   |   |   |   |   |   |   |   |   SO2 < 6.05
|   |   |   |   |   |   |   |   |   |   SO2 < 3.95
|   |   |   |   |   |   |   |   |   |   |   Nox < 31.46
|   |   |   |   |   |   |   |   |   |   |   |   CH4 < 2
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 3.6
|   |   |   |   |   |   |   |   |   |   |   |   |   |   CO < 0.57 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   CO >= 0.57 : 43 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 3.6
|   |   |   |   |   |   |   |   |   |   |   |   |   |   CO < 0.57 : 40 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   CO >= 0.57
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 < 31.8 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 >= 31.8 : 42 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   CH4 >= 2
|   |   |   |   |   |   |   |   |   |   |   |   |   TEMP < 20.96
|   |   |   |   |   |   |   |   |   |   |   |   |   |   NO < 4.08
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 < 24.95 : 45 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 >= 24.95 : 44 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   NO >= 4.08
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 3.45 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 3.45
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   THC < 2.27 : 42 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   THC >= 2.27 : 43 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   TEMP >= 20.96
|   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 < 28.85 : 45 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 >= 28.85 : 46 (1/0)
|   |   |   |   |   |   |   |   |   |   |   Nox >= 31.46
|   |   |   |   |   |   |   |   |   |   |   |   NO2 < 25.38 : 33 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   NO2 >= 25.38 : 44 (1/0)
|   |   |   |   |   |   |   |   |   |   SO2 >= 3.95
|   |   |   |   |   |   |   |   |   |   |   O3 < 28.7
|   |   |   |   |   |   |   |   |   |   |   |   Nox < 40.56
|   |   |   |   |   |   |   |   |   |   |   |   |   CH4 < 1.96
|   |   |   |   |   |   |   |   |   |   |   |   |   |   THC < 2.22
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 5.15 : 39 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 5.15 : 40 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   THC >= 2.22 : 32 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   CH4 >= 1.96
|   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox < 36.07
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox < 28.44 : 38 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox >= 28.44
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   CO < 0.81
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 < 27.45
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NMHC < 0.33
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO < 5.39
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   WindSpeed < 1.56 : 43 (2/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   WindSpeed >= 1.56
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   TEMP < 20.77
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO2 < 24.73 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO2 >= 24.73 : 42 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   TEMP >= 20.77 : 40 (3/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO >= 5.39
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   CH4 < 2.03
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO < 5.99 : 39 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO >= 5.99
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 4.35 : 40 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 4.35 : 42 (2/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   CH4 >= 2.03
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox < 35.13
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   CO < 0.63
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 4.35 : 39 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 4.35 : 40 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   CO >= 0.63 : 39 (3/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox >= 35.13 : 38 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NMHC >= 0.33
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   CO < 0.61 : 43 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   CO >= 0.61 : 42 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 >= 27.45
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox < 30.27 : 44 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox >= 30.27 : 45 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   CO >= 0.81
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 4.4 : 43 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 4.4 : 45 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox >= 36.07
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox < 36.72 : 34 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox >= 36.72
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 < 25.9
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 4.45 : 40 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 4.45 : 38 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   O3 >= 25.9 : 43 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   Nox >= 40.56 : 44 (2/0)
|   |   |   |   |   |   |   |   |   |   |   O3 >= 28.7
|   |   |   |   |   |   |   |   |   |   |   |   THC < 2.28 : 38 (2/0)
|   |   |   |   |   |   |   |   |   |   |   |   THC >= 2.28
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 5.2 : 37 (2/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 5.2 : 36 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 6.05
|   |   |   |   |   |   |   |   |   |   CO < 0.61 : 44 (1/0)
|   |   |   |   |   |   |   |   |   |   CO >= 0.61
|   |   |   |   |   |   |   |   |   |   |   O3 < 25.3 : 47 (1/0)
|   |   |   |   |   |   |   |   |   |   |   O3 >= 25.3 : 48 (1/0)
|   |   |   |   |   |   |   |   SO2 >= 6.35
|   |   |   |   |   |   |   |   |   NMHC < 0.26
|   |   |   |   |   |   |   |   |   |   Nox < 30.57 : 33 (1/0)
|   |   |   |   |   |   |   |   |   |   Nox >= 30.57 : 36 (2/0)
|   |   |   |   |   |   |   |   |   NMHC >= 0.26
|   |   |   |   |   |   |   |   |   |   SO2 < 7.95 : 40 (1/0)
|   |   |   |   |   |   |   |   |   |   SO2 >= 7.95 : 43 (1/0)
|   |   |   |   |   Humidity >= 74.5
|   |   |   |   |   |   CH4 < 1.98
|   |   |   |   |   |   |   SO2 < 5.7
|   |   |   |   |   |   |   |   CO < 0.61
|   |   |   |   |   |   |   |   |   SO2 < 3.15 : 32 (1/0)
|   |   |   |   |   |   |   |   |   SO2 >= 3.15 : 34 (1/0)
|   |   |   |   |   |   |   |   CO >= 0.61 : 29 (1/0)
|   |   |   |   |   |   |   SO2 >= 5.7 : 24 (2/0)
|   |   |   |   |   |   CH4 >= 1.98
|   |   |   |   |   |   |   NO2 < 28.63
|   |   |   |   |   |   |   |   NMHC < 0.15 : 30 (1/0)
|   |   |   |   |   |   |   |   NMHC >= 0.15
|   |   |   |   |   |   |   |   |   NO2 < 27.34
|   |   |   |   |   |   |   |   |   |   O3 < 24.95
|   |   |   |   |   |   |   |   |   |   |   WindSpeed < 2.62
|   |   |   |   |   |   |   |   |   |   |   |   TEMP < 18.95
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 7.6
|   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox < 27.4 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox >= 27.4
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox < 30.66 : 39 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   Nox >= 30.66 : 38 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 7.6 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   TEMP >= 18.95
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 4.15 : 36 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 4.15 : 37 (1/0)
|   |   |   |   |   |   |   |   |   |   |   WindSpeed >= 2.62 : 34 (1/0)
|   |   |   |   |   |   |   |   |   |   O3 >= 24.95
|   |   |   |   |   |   |   |   |   |   |   O3 < 25.85 : 43 (2/0)
|   |   |   |   |   |   |   |   |   |   |   O3 >= 25.85
|   |   |   |   |   |   |   |   |   |   |   |   THC < 2.39
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 4.9
|   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 2.75 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 2.75
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO2 < 21.38
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO2 < 20.29 : 39 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO2 >= 20.29 : 40 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   NO2 >= 21.38 : 39 (3/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 4.9
|   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 < 6.2 : 42 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   |   |   SO2 >= 6.2 : 41 (1/0)
|   |   |   |   |   |   |   |   |   |   |   |   THC >= 2.39 : 36 (1/0)
|   |   |   |   |   |   |   |   |   NO2 >= 27.34 : 32 (1/0)
|   |   |   |   |   |   |   NO2 >= 28.63
|   |   |   |   |   |   |   |   NO < 12.54
|   |   |   |   |   |   |   |   |   THC < 2.28 : 41 (1/0)
|   |   |   |   |   |   |   |   |   THC >= 2.28 : 40 (1/0)
|   |   |   |   |   |   |   |   NO >= 12.54 : 45 (1/0)
|   |   |   O3 >= 32.45
|   |   |   |   SO2 < 4.55
|   |   |   |   |   WindSpeed < 1.85
|   |   |   |   |   |   SO2 < 4.3 : 36 (1/0)
|   |   |   |   |   |   SO2 >= 4.3 : 35 (1/0)
|   |   |   |   |   WindSpeed >= 1.85
|   |   |   |   |   |   THC < 2.25
|   |   |   |   |   |   |   CO < 0.5 : 43 (1/0)
|   |   |   |   |   |   |   CO >= 0.5 : 40 (2/0)
|   |   |   |   |   |   THC >= 2.25 : 45 (1/0)
|   |   |   |   SO2 >= 4.55
|   |   |   |   |   NO2 < 22.84
|   |   |   |   |   |   CH4 < 2.12
|   |   |   |   |   |   |   TEMP < 26.44
|   |   |   |   |   |   |   |   NMHC < 0.18 : 23 (1/0)
|   |   |   |   |   |   |   |   NMHC >= 0.18 : 24 (1/0)
|   |   |   |   |   |   |   TEMP >= 26.44
|   |   |   |   |   |   |   |   O3 < 35.4 : 26 (1/0)
|   |   |   |   |   |   |   |   O3 >= 35.4 : 29 (4/0)
|   |   |   |   |   |   CH4 >= 2.12
|   |   |   |   |   |   |   SO2 < 5.4 : 33 (1/0)
|   |   |   |   |   |   |   SO2 >= 5.4
|   |   |   |   |   |   |   |   CO < 0.47 : 37 (1/0)
|   |   |   |   |   |   |   |   CO >= 0.47 : 36 (1/0)
|   |   |   |   |   NO2 >= 22.84
|   |   |   |   |   |   WindSpeed < 1.71
|   |   |   |   |   |   |   WindSpeed < 1.34 : 38 (1/0)
|   |   |   |   |   |   |   WindSpeed >= 1.34
|   |   |   |   |   |   |   |   THC < 2.27 : 28 (1/0)
|   |   |   |   |   |   |   |   THC >= 2.27
|   |   |   |   |   |   |   |   |   O3 < 33.9 : 32 (1/0)
|   |   |   |   |   |   |   |   |   O3 >= 33.9 : 31 (1/0)
|   |   |   |   |   |   WindSpeed >= 1.71
|   |   |   |   |   |   |   THC < 2.27
|   |   |   |   |   |   |   |   CO < 0.57 : 41 (1/0)
|   |   |   |   |   |   |   |   CO >= 0.57 : 43 (1/0)
|   |   |   |   |   |   |   THC >= 2.27 : 33 (1/0)

Size of the tree : 653

Time taken to build model: 0.02 seconds

=== Evaluation on training set ===

Time taken to test model on training data: 0 seconds

=== Summary ===

Correlation coefficient                  1     
Mean absolute error                      0     
Root mean squared error                  0     
Relative absolute error                  0      %
Root relative squared error              0      %
Total Number of Instances              401     

