![Title](./src/assets/title.png "Title") <br>

Bayesian Optimization Executable and Visualizable Application (BOXVIA) is a GUI-based application for Bayesian optimization. By using BOXVIA, users can perform Bayesian optimization and visualize functions obtained from the optimization process (i.e. mean function, its standard deviation, and acquisition function) without construction of a computing environment and programming skills. BOXVIA offers significant help for incorporating Bayesian optimization into your optimization problem.

## Download an executable application
You can download executable files for BOXVIA from [Releases](https://github.com/Yamanaka-Lab-TUAT/BOXVIA/releases).

## How to start BOXVIA
### For using executable file
Extract the downloaded file and double-click on "BOXVIA" executable file. <br>
The name of the executable is "BOXVIA.exe" on windows, "BOXVIA.app" on macOS, and "BOXVIA" on linux.

### For running source code
 Start with
```bash
python main.py
```

## Dependencies 
To start BOXVIA via the source codes, the following libraries are required. <br>
If you use executable file, no dependencies are required. <br>

- GPyOpt
- matplotlib
- pandas
- Dash
- Dash_bootstrap_components


You can install the dependencies by:
```bash
pip install -r requirements.txt
```
<br>
Note: <br>

If you use BOXVIA by starting from the source code, the following two codes of
[GPyOpt](https://github.com/SheffieldML/GPyOpt) need to be modified. <br>

- GPyOpt/core/bo.py
- GPyOpt/core/evaluators/batch_local_penalization.py

Please replace these codes with the codes contained in src/GPyOpt_modified in this repository.


## Tutorial
Please see video tutorials uploaded on YouTube. <br>
[Video tutorial for 1D function](https://www.youtube.com/watch?v=ljzGmVSf16U) <br>
[Video tutorial for 5D function](https://www.youtube.com/watch?v=merYNmawvkw)

## License
BSD License (3-clause BSD License)

## Developers' Affiliation
[Yamanaka Research Group @ TUAT](http://web.tuat.ac.jp/~yamanaka/)
