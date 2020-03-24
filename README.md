# COVID-19

The data used for this project has been taken from CSSEGISandData's repository: https://github.com/CSSEGISandData/COVID-19 <br/>

To update dataset:
* Create virtual environment and install debendencies:
```console
$ python3 -m venv env
$ git clone https://github.com/Meerkats1999/COVID-19-AnalysisStuff.git
$ pip3 install -r requirements.txt
```
* Fetch data:
```console
$ python3 fetchData.py
```
No inferences have been included as the dataset updates on a day to day basis.<br/>
I plan to include some sort of prediction in the future.

