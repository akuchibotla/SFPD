# San Francisco Police Dept. Crime Prediction (CS 194 Project)

Anand Kuchibotla, Harish Shanker, Kunal Roy, Alex Romano

### Installation

Clone this repository
```sh
$ git clone git@github.com:akuchibotla/SFPD.git
```

Download CSV from https://data.sfgov.org/api/views/tmnf-yvry/rows.csv (Servers are slow so it could take a little bit of time before the download starts). Make sure that the CSV is in the SFPD folder and rename it data.csv

```sh
$ mv SFPD_Incidents_-_from_1_January_2003.csv data.csv
```

Now, enter the SFPD folder and run iPython

```sh
$ cd SFPD
$ ipython notebook
```

### Dependencies
 - numpy
 - pandas
 - matplotlib.pyplot

For numpy and pandas, you can downlaod it using the pip installer.

```sh
$ sudo pip install numpy
$ sudo pip install pandas
```

