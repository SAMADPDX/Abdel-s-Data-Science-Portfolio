```python
import pandas as pd
```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    Cell In[1], line 1
    ----> 1 import pandas as pd


    ModuleNotFoundError: No module named 'pandas'



```python
import pandas as pd
```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    Cell In[2], line 1
    ----> 1 import pandas as pd


    ModuleNotFoundError: No module named 'pandas'



```python
pip install pandas
```

    Collecting pandas
      Downloading pandas-1.5.2-cp310-cp310-macosx_11_0_arm64.whl (10.8 MB)
    [2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m10.8/10.8 MB[0m [31m67.2 MB/s[0m eta [36m0:00:00[0ma [36m0:00:01[0m
    [?25hRequirement already satisfied: python-dateutil>=2.8.1 in /opt/homebrew/Cellar/jupyterlab/3.4.8/libexec/lib/python3.10/site-packages (from pandas) (2.8.2)
    Requirement already satisfied: pytz>=2020.1 in /opt/homebrew/Cellar/jupyterlab/3.4.8/libexec/lib/python3.10/site-packages (from pandas) (2022.4)
    Collecting numpy>=1.21.0
      Downloading numpy-1.24.1-cp310-cp310-macosx_11_0_arm64.whl (13.9 MB)
    [2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m13.9/13.9 MB[0m [31m74.9 MB/s[0m eta [36m0:00:00[0m00:01[0m00:01[0m
    [?25hRequirement already satisfied: six>=1.5 in /opt/homebrew/Cellar/six/1.16.0_3/lib/python3.10/site-packages (from python-dateutil>=2.8.1->pandas) (1.16.0)
    Installing collected packages: numpy, pandas
    Successfully installed numpy-1.24.1 pandas-1.5.2
    
    [1m[[0m[34;49mnotice[0m[1;39;49m][0m[39;49m A new release of pip available: [0m[31;49m22.2.2[0m[39;49m -> [0m[32;49m22.3.1[0m
    [1m[[0m[34;49mnotice[0m[1;39;49m][0m[39;49m To update, run: [0m[32;49mpython3.10 -m pip install --upgrade pip[0m
    Note: you may need to restart the kernel to use updated packages.



```python
import pandas as pd
```


```python
 from matplotlib import pyplot as plt
```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    Cell In[2], line 1
    ----> 1 from matplotlib import pyplot as plt


    ModuleNotFoundError: No module named 'matplotlib'



```python
pip install matplotlib
```

    Collecting matplotlib
      Downloading matplotlib-3.6.2-cp310-cp310-macosx_11_0_arm64.whl (7.2 MB)
    [2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m7.2/7.2 MB[0m [31m34.8 MB/s[0m eta [36m0:00:00[0ma [36m0:00:01[0m
    [?25hRequirement already satisfied: pyparsing>=2.2.1 in /opt/homebrew/Cellar/jupyterlab/3.4.8/libexec/lib/python3.10/site-packages (from matplotlib) (3.0.9)
    Requirement already satisfied: numpy>=1.19 in /opt/homebrew/Cellar/jupyterlab/3.4.8/libexec/lib/python3.10/site-packages (from matplotlib) (1.24.1)
    Requirement already satisfied: python-dateutil>=2.7 in /opt/homebrew/Cellar/jupyterlab/3.4.8/libexec/lib/python3.10/site-packages (from matplotlib) (2.8.2)
    Collecting cycler>=0.10
      Downloading cycler-0.11.0-py3-none-any.whl (6.4 kB)
    Collecting kiwisolver>=1.0.1
      Downloading kiwisolver-1.4.4-cp310-cp310-macosx_11_0_arm64.whl (63 kB)
    [2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m63.2/63.2 kB[0m [31m7.1 MB/s[0m eta [36m0:00:00[0m
    [?25hCollecting contourpy>=1.0.1
      Downloading contourpy-1.0.6-cp310-cp310-macosx_11_0_arm64.whl (225 kB)
    [2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m225.9/225.9 kB[0m [31m25.9 MB/s[0m eta [36m0:00:00[0m
    [?25hRequirement already satisfied: packaging>=20.0 in /opt/homebrew/Cellar/jupyterlab/3.4.8/libexec/lib/python3.10/site-packages (from matplotlib) (21.3)
    Collecting pillow>=6.2.0
      Downloading Pillow-9.3.0-cp310-cp310-macosx_11_0_arm64.whl (2.9 MB)
    [2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m2.9/2.9 MB[0m [31m54.6 MB/s[0m eta [36m0:00:00[0ma [36m0:00:01[0m
    [?25hCollecting fonttools>=4.22.0
      Downloading fonttools-4.38.0-py3-none-any.whl (965 kB)
    [2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m965.4/965.4 kB[0m [31m30.1 MB/s[0m eta [36m0:00:00[0m
    [?25hRequirement already satisfied: six>=1.5 in /opt/homebrew/Cellar/six/1.16.0_3/lib/python3.10/site-packages (from python-dateutil>=2.7->matplotlib) (1.16.0)
    Installing collected packages: pillow, kiwisolver, fonttools, cycler, contourpy, matplotlib
    Successfully installed contourpy-1.0.6 cycler-0.11.0 fonttools-4.38.0 kiwisolver-1.4.4 matplotlib-3.6.2 pillow-9.3.0
    
    [1m[[0m[34;49mnotice[0m[1;39;49m][0m[39;49m A new release of pip available: [0m[31;49m22.2.2[0m[39;49m -> [0m[32;49m22.3.1[0m
    [1m[[0m[34;49mnotice[0m[1;39;49m][0m[39;49m To update, run: [0m[32;49mpython3.10 -m pip install --upgrade pip[0m
    Note: you may need to restart the kernel to use updated packages.



```python
 from matplotlib import pyplot as plt
```


```python
x = [1, 2, 3]
y = [1, 4, 9]
z = [10, 5, 0]

plt.plot(x, y)
plt.plot(x, z)
plt.title("Data Visualization Practice")
plt.xlabel("x")
plt.ylabel("y and z")
plt.legend(["this is y", "this is z"])
plt.show()
```


    
![png](output_7_0.png)
    



```python
sample_data = pd.read_csv('sample_data.csv')
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[10], line 1
    ----> 1 sample_data = pd.read_csv('sample_data.csv')


    NameError: name 'pd' is not defined



```python
import pandas as pd
```


```python
sample_data = pd.read_csv('sample_data.csv')
```


```python
sample_data
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>column_a</th>
      <th>column_b</th>
      <th>column_c</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>10</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>4</td>
      <td>8</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>9</td>
      <td>6</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>16</td>
      <td>4</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>25</td>
      <td>2</td>
    </tr>
  </tbody>
</table>
</div>




```python
type(sample_data)
```




    pandas.core.frame.DataFrame




```python
sample_data.column_c
```




    0    10
    1     8
    2     6
    3     4
    4     2
    Name: column_c, dtype: int64




```python
type(sample_data.column_c)
```




    pandas.core.series.Series




```python
sample_data.column_c.iloc[1]
```




    8




```python
plt.plot(sample_data.column_a, sample_data.column_b, "o")
plt.plot(sample_data.column_a, sample_data.column_c)
plt.show()
```


    
![png](output_16_0.png)
    



```python
countries_data = pd.read_csv("countries.csv")
```


```python
countries_data
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>country</th>
      <th>year</th>
      <th>population</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Afghanistan</td>
      <td>1952</td>
      <td>8425333</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Afghanistan</td>
      <td>1957</td>
      <td>9240934</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Afghanistan</td>
      <td>1962</td>
      <td>10267083</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Afghanistan</td>
      <td>1967</td>
      <td>11537966</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Afghanistan</td>
      <td>1972</td>
      <td>13079460</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>1699</th>
      <td>Zimbabwe</td>
      <td>1987</td>
      <td>9216418</td>
    </tr>
    <tr>
      <th>1700</th>
      <td>Zimbabwe</td>
      <td>1992</td>
      <td>10704340</td>
    </tr>
    <tr>
      <th>1701</th>
      <td>Zimbabwe</td>
      <td>1997</td>
      <td>11404948</td>
    </tr>
    <tr>
      <th>1702</th>
      <td>Zimbabwe</td>
      <td>2002</td>
      <td>11926563</td>
    </tr>
    <tr>
      <th>1703</th>
      <td>Zimbabwe</td>
      <td>2007</td>
      <td>12311143</td>
    </tr>
  </tbody>
</table>
<p>1704 rows × 3 columns</p>
</div>




```python
#Compare Population Growth In The US VS CHINA.
```


```python
countires_data.country
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[33], line 1
    ----> 1 countires_data.country


    NameError: name 'countires_data' is not defined



```python
countries_data.country == 'United States'
```




    0       False
    1       False
    2       False
    3       False
    4       False
            ...  
    1699    False
    1700    False
    1701    False
    1702    False
    1703    False
    Name: country, Length: 1704, dtype: bool




```python
US = countries_data[countries_data.country == 'United States']

```


```python

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>country</th>
      <th>year</th>
      <th>population</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>
</div>




```python
US
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>country</th>
      <th>year</th>
      <th>population</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1608</th>
      <td>United States</td>
      <td>1952</td>
      <td>157553000</td>
    </tr>
    <tr>
      <th>1609</th>
      <td>United States</td>
      <td>1957</td>
      <td>171984000</td>
    </tr>
    <tr>
      <th>1610</th>
      <td>United States</td>
      <td>1962</td>
      <td>186538000</td>
    </tr>
    <tr>
      <th>1611</th>
      <td>United States</td>
      <td>1967</td>
      <td>198712000</td>
    </tr>
    <tr>
      <th>1612</th>
      <td>United States</td>
      <td>1972</td>
      <td>209896000</td>
    </tr>
    <tr>
      <th>1613</th>
      <td>United States</td>
      <td>1977</td>
      <td>220239000</td>
    </tr>
    <tr>
      <th>1614</th>
      <td>United States</td>
      <td>1982</td>
      <td>232187835</td>
    </tr>
    <tr>
      <th>1615</th>
      <td>United States</td>
      <td>1987</td>
      <td>242803533</td>
    </tr>
    <tr>
      <th>1616</th>
      <td>United States</td>
      <td>1992</td>
      <td>256894189</td>
    </tr>
    <tr>
      <th>1617</th>
      <td>United States</td>
      <td>1997</td>
      <td>272911760</td>
    </tr>
    <tr>
      <th>1618</th>
      <td>United States</td>
      <td>2002</td>
      <td>287675526</td>
    </tr>
    <tr>
      <th>1619</th>
      <td>United States</td>
      <td>2007</td>
      <td>301139947</td>
    </tr>
  </tbody>
</table>
</div>




```python
China = countries_data[countries_data.country == 'China']
```


```python
China
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>country</th>
      <th>year</th>
      <th>population</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>288</th>
      <td>China</td>
      <td>1952</td>
      <td>556263527</td>
    </tr>
    <tr>
      <th>289</th>
      <td>China</td>
      <td>1957</td>
      <td>637408000</td>
    </tr>
    <tr>
      <th>290</th>
      <td>China</td>
      <td>1962</td>
      <td>665770000</td>
    </tr>
    <tr>
      <th>291</th>
      <td>China</td>
      <td>1967</td>
      <td>754550000</td>
    </tr>
    <tr>
      <th>292</th>
      <td>China</td>
      <td>1972</td>
      <td>862030000</td>
    </tr>
    <tr>
      <th>293</th>
      <td>China</td>
      <td>1977</td>
      <td>943455000</td>
    </tr>
    <tr>
      <th>294</th>
      <td>China</td>
      <td>1982</td>
      <td>1000281000</td>
    </tr>
    <tr>
      <th>295</th>
      <td>China</td>
      <td>1987</td>
      <td>1084035000</td>
    </tr>
    <tr>
      <th>296</th>
      <td>China</td>
      <td>1992</td>
      <td>1164970000</td>
    </tr>
    <tr>
      <th>297</th>
      <td>China</td>
      <td>1997</td>
      <td>1230075000</td>
    </tr>
    <tr>
      <th>298</th>
      <td>China</td>
      <td>2002</td>
      <td>1280400000</td>
    </tr>
    <tr>
      <th>299</th>
      <td>China</td>
      <td>2007</td>
      <td>1318683096</td>
    </tr>
  </tbody>
</table>
</div>




```python
plt.plot(US.year, US.population / 10**6)
plt.show()
```


    
![png](output_27_0.png)
    



```python
plt.plot(China.year, China.population / 10**6)
plt.show()
```


    
![png](output_28_0.png)
    



```python
plt.plot(US.year, US.population / 10**6)
plt.plot(China.year, China.population / 10**6)
plt.legend(['United States', 'China'])
plt.xlabel('Year')
plt.ylabel('Population')
plt.show()
```


    
![png](output_29_0.png)
    



```python
US.population
```




    1608    157553000
    1609    171984000
    1610    186538000
    1611    198712000
    1612    209896000
    1613    220239000
    1614    232187835
    1615    242803533
    1616    256894189
    1617    272911760
    1618    287675526
    1619    301139947
    Name: population, dtype: int64




```python
US.population / US.population.iloc[0] * 100
```




    1608    100.000000
    1609    109.159457
    1610    118.396984
    1611    126.123908
    1612    133.222471
    1613    139.787246
    1614    147.371256
    1615    154.109114
    1616    163.052553
    1617    173.219018
    1618    182.589685
    1619    191.135648
    Name: population, dtype: float64




```python
plt.plot(US.year, US.population / US.population.iloc[0] * 100)
plt.plot(China.year, China.population / China.population.iloc[0] * 100)
plt.legend(['United States', 'China'])
plt.xlabel('Year')
plt.ylabel('Population Growth (First Year = 100)')
plt.show()
```


    
![png](output_32_0.png)
    



```python

```
