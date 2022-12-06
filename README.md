## Getting Started

Create directory folder and call it data
install the CSV files in the data folder
if you don't have Node.js installed in your computer, pleace install it from https://nodejs.org

From within this project's directory root, run

```bash
npm install
```

Then, for classification results , run

```bash
node ./[file name].js
```

## Data

[A01T.mat](data/A01T.mat) and [A01E.mat](data/A01E.mat) contain the training and evaluation data respectively. They were converted to a CSV format using the Octave/MATLAB script [SubjectDataToCSV.m](SubjectDataToCSV.m).

Data files were downloaded from [http://bnci-horizon-2020.eu/database/data-sets](http://bnci-horizon-2020.eu/database/data-sets)<br />
License: [Creative Commons Attribution No Derivatives license (CC BY-ND 4.0)](https://creativecommons.org/licenses/by-nd/4.0/).<br />
Licensor: [Institute for Knowledge Discovery, Graz University of Technology](http://bci.tugraz.at/)
