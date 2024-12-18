# 🗃️ Boston Housing Dataset

- A classic dataset widely used for evaluating regression algorithms and statistical methodologies.  
- **Number of Instances:** 506
- **Reference Paper**:
  - [**Hedonic housing prices and the demand for clean air**](https://www.sciencedirect.com/science/article/abs/pii/0095069678900062) by [*David Harrison Jr.*](https://www.scopus.com/authid/detail.uri?authorId=57214410562) and [*Daniel L Rubinfeld*](https://www.scopus.com/authid/detail.uri?authorId=6603666462) in 1978.
- **Creators**:
  - [David Harrison Jr.](https://www.scopus.com/authid/detail.uri?authorId=57214410562)
  - [Daniel L Rubinfeld](https://www.scopus.com/authid/detail.uri?authorId=6603666462)

## 🔍 More Details

<table style="margin: 0 auto;">
  <thead>
    <tr>
      <th style="text-align: center;">#</th>
      <th style="text-align: center;">Attribute Name</th>
      <th style="text-align: center;">Role</th>
      <th style="text-align: center;">Type</th>
      <th style="text-align: center;">Units</th>
      <th style="text-align: center;">Missing Values</th>
      <th style="text-align: center;">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>CRIM</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>per capita</td>
      <td>false</td>
      <td>Per capita crime rate by town</td>
    </tr>
    <tr>
      <td>1</td>
      <td>ZN</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>percent</td>
      <td>false</td>
      <td>Proportion of residential land zoned for lots over 25,000 sq.ft.</td>
    </tr>
    <tr>
      <td>2</td>
      <td>INDUS</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>percent</td>
      <td>false</td>
      <td>Proportion of non-retail business acres per town</td>
    </tr>
    <tr>
      <td>3</td>
      <td>CHAS</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)</td>
    </tr>
    <tr>
      <td>4</td>
      <td>NOX</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>parts per 10 million</td>
      <td>false</td>
      <td>Nitric oxides concentration (parts per 10 million)</td>
    </tr>
    <tr>
      <td>5</td>
      <td>RM</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>units</td>
      <td>false</td>
      <td>Average number of rooms per dwelling</td>
    </tr>
    <tr>
      <td>6</td>
      <td>AGE</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>percent</td>
      <td>false</td>
      <td>Proportion of owner-occupied units built prior to 1940</td>
    </tr>
    <tr>
      <td>7</td>
      <td>DIS</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>index</td>
      <td>false</td>
      <td>Weighted distances to five Boston employment centers</td>
    </tr>
    <tr>
      <td>8</td>
      <td>RAD</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>index</td>
      <td>false</td>
      <td>Index of accessibility to radial highways</td>
    </tr>
    <tr>
      <td>9</td>
      <td>TAX</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>rate per $10,000</td>
      <td>false</td>
      <td>Full-value property-tax rate per $10,000</td>
    </tr>
    <tr>
      <td>10</td>
      <td>PTRATIO</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>ratio</td>
      <td>false</td>
      <td>Pupil-teacher ratio by town</td>
    </tr>
    <tr>
      <td>11</td>
      <td>B</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>N/A</td>
      <td>false</td>
      <td>1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town</td>
    </tr>
    <tr>
      <td>12</td>
      <td>LSTAT</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>percent</td>
      <td>false</td>
      <td>% lower status of the population</td>
    </tr>
    <tr>
      <td>13</td>
      <td>MEDV</td>
      <td><strong>Target</strong></td>
      <td>Numerical</td>
      <td>$1000s</td>
      <td>false</td>
      <td>Median value of owner-occupied homes in $1000's</td>
    </tr>
  </tbody>
</table>

### 🔍 Categorical Attributes

<table style="margin: 0 auto;">
  <thead>
    <tr>
      <th style="text-align: center;">#</th>
      <th style="text-align: center;">Attribute Name</th>
      <th style="text-align: center;"># Categories</th>
      <th style="text-align: center;">Categories Name</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>3</td>
      <td>CHAS</td>
      <td>2</td>
      <td>0 (does not bound river), 1 (bounds river)</td>
    </tr>
  </tbody>
</table>

## 🔍 Some Samples

<table style="margin: 0 auto;">
  <thead>
    <tr>
      <th>CRIM</th>
      <th>ZN</th>
      <th>INDUS</th>
      <th>CHAS</th>
      <th>NOX</th>
      <th>RM</th>
      <th>AGE</th>
      <th>DIS</th>
      <th>RAD</th>
      <th>TAX</th>
      <th>PTRATIO</th>
      <th>B</th>
      <th>LSTAT</th>
      <th>MEDV</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0.00632</td>
      <td>18.0</td>
      <td>2.31</td>
      <td>0</td>
      <td>0.538</td>
      <td>6.575</td>
      <td>65.2</td>
      <td>4.0900</td>
      <td>1</td>
      <td>296</td>
      <td>15.3</td>
      <td>396.90</td>
      <td>4.98</td>
      <td>24.0</td>
    </tr>
    <tr>
      <td>0.02731</td>
      <td>0.0</td>
      <td>7.07</td>
      <td>0</td>
      <td>0.469</td>
      <td>6.421</td>
      <td>78.9</td>
      <td>4.9671</td>
      <td>2</td>
      <td>242</td>
      <td>17.8</td>
      <td>396.90</td>
      <td>9.14</td>
      <td>21.6</td>
    </tr>
    <tr>
      <td>0.02729</td>
      <td>0.0</td>
      <td>7.07</td>
      <td>0</td>
      <td>0.469</td>
      <td>7.185</td>
      <td>61.1</td>
      <td>4.9671</td>
      <td>2</td>
      <td>242</td>
      <td>17.8</td>
      <td>392.83</td>
      <td>4.03</td>
      <td>34.7</td>
    </tr>
    <tr>
      <td>0.03237</td>
      <td>0.0</td>
      <td>2.18</td>
      <td>0</td>
      <td>0.458</td>
      <td>6.998</td>
      <td>45.8</td>
      <td>6.0622</td>
      <td>3</td>
      <td>222</td>
      <td>18.7</td>
      <td>394.63</td>
      <td>2.94</td>
      <td>33.4</td>
    </tr>
    <tr>
      <td>0.06905</td>
      <td>0.0</td>
      <td>2.18</td>
      <td>0</td>
      <td>0.458</td>
      <td>7.147</td>
      <td>54.2</td>
      <td>6.0622</td>
      <td>3</td>
      <td>222</td>
      <td>18.7</td>
      <td>396.90</td>
      <td>5.33</td>
      <td>36.2</td>
    </tr>
  </tbody>
</table>

## 📄 License

This dataset does not appear to have a specific license or formal usage agreement provided by its creators or maintainers.  
Users are encouraged to verify usage terms if needed.

## ©️ Credit

Visit [**Data for Evaluating Learning in Valid Experiments (DELV) Archive**](https://www.cs.toronto.edu/~delve/data/boston/) for more information.
