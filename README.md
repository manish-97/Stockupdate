# stock-app



### Create conda environment
Firstly, we will create a conda environment called *stock*
```
conda create -n stock python=3.7.9
```
Secondly, we will login to the *stock* environement
```
conda activate stock
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/stock-app/main/requirements.txt

```

pip install libraries(in the requirements.txt)
```


###  Launch the app

```
streamlit run app.py
```
