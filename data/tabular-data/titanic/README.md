# 🗃️ Titanic Dataset

- A widely-used dataset for binary classification tasks, particularly survival prediction.
- **Number of Instances:** 891 in the training set, 418 in the test set.
- **Data Split:** Pre-split into `train.csv` and `test.csv`.
- **Missing Values** are considered as `NaN` in the dataset.
- **Creator**:
  - [Will Cukierski](https://scholar.google.com/citations?user=btZpioYAAAAJ&hl=en)

## 🔍 More Details

<table style="margin: 0 auto;">
  <thead>
    <tr>
      <th rowspan="2" style="text-align: center;">#</th>
      <th rowspan="2" style="text-align: center;">Attribute Name</th>
      <th rowspan="2" style="text-align: center;">Role</th>
      <th rowspan="2" style="text-align: center;">Type</th>
      <th rowspan="2" style="text-align: center;">Units</th>
      <th colspan="2" style="text-align: center;">Missing Values</th>
      <th rowspan="2" style="text-align: center;">Description</th>
    </tr>
    <tr>
      <th style="text-align: center;">train.csv</th>
      <th style="text-align: center;">test.csv</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>PassengerId</td>
      <td>Identifier</td>
      <td>Numerical</td>
      <td>N/A</td>
      <td>false</td>
      <td>false</td>
      <td>Unique ID for each passenger</td>
    </tr>
    <tr>
      <td>1</td>
      <td>Survived</td>
      <td><strong>Target</strong></td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>false</td>
      <td>Survival status (0 = No, 1 = Yes)</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Pclass</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>false</td>
      <td>Passenger class (1, 2, 3)</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Name</td>
      <td>Feature</td>
      <td>Text</td>
      <td>N/A</td>
      <td>false</td>
      <td>false</td>
      <td>Passenger's full name</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Sex</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>false</td>
      <td>Gender (male, female)</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Age</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>years</td>
      <td>true (19.87%)</td>
      <td>true (20.57%)</td>
      <td>Passenger's age</td>
    </tr>
    <tr>
      <td>6</td>
      <td>SibSp</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>N/A</td>
      <td>false</td>
      <td>false</td>
      <td>Number of siblings/spouses aboard</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Parch</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>N/A</td>
      <td>false</td>
      <td>false</td>
      <td>Number of parents/children aboard</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Ticket</td>
      <td>Feature</td>
      <td>Text</td>
      <td>N/A</td>
      <td>false</td>
      <td>false</td>
      <td>Ticket number</td>
    </tr>
    <tr>
      <td>9</td>
      <td>Fare</td>
      <td>Feature</td>
      <td>Numerical</td>
      <td>currency</td>
      <td>false</td>
      <td>true (0.24%)</td>
      <td>Ticket fare</td>
    </tr>
    <tr>
      <td>10</td>
      <td>Cabin</td>
      <td>Feature</td>
      <td>Text</td>
      <td>N/A</td>
      <td>true (77.1%)</td>
      <td>true (78.23%)</td>
      <td>Cabin number</td>
    </tr>
    <tr>
      <td>11</td>
      <td>Embarked</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>true (0.22%)</td>
      <td>false</td>
      <td>Port of embarkation (C, Q, S)</td>
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
      <td>1</td>
      <td>Survived</td>
      <td>2</td>
      <td>0, 1</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Pclass</td>
      <td>3</td>
      <td>1, 2, 3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Sex</td>
      <td>2</td>
      <td>male, female</td>
    </tr>
    <tr>
      <td>11</td>
      <td>Embarked</td>
      <td>3</td>
      <td>Q, S, C</td>
    </tr>
  </tbody>
</table>

## 🔍 Some Samples

These samples are chosen from the [**train.csv**](./train.csv) file to give an overview of the dataset's structure and values.
<table style="margin: 0 auto;">
  <thead>
    <tr>
      <th style="text-align: center;"># Sample</th>
      <th style="text-align: center;">PassengerId</th>
      <th style="text-align: center;">Survived</th>
      <th style="text-align: center;">Pclass</th>
      <th style="text-align: center;">Name</th>
      <th style="text-align: center;">Sex</th>
      <th style="text-align: center;">Age</th>
      <th style="text-align: center;">SibSp</th>
      <th style="text-align: center;">Parch</th>
      <th style="text-align: center;">Ticket</th>
      <th style="text-align: center;">Fare</th>
      <th style="text-align: center;">Cabin</th>
      <th style="text-align: center;">Embarked</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>3</td>
      <td>Braund, Mr. Owen Harris</td>
      <td>male</td>
      <td>22</td>
      <td>1</td>
      <td>0</td>
      <td>A/5 21171</td>
      <td>7.25</td>
      <td>NaN</td>
      <td>S</td>
    </tr>
    <tr>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>Cumings, Mrs. John Bradley (Florence Briggs Thayer)</td>
      <td>female</td>
      <td>38</td>
      <td>1</td>
      <td>0</td>
      <td>PC 17599</td>
      <td>71.2833</td>
      <td>C85</td>
      <td>C</td>
    </tr>
    <tr>
      <td>3</td>
      <td>3</td>
      <td>1</td>
      <td>3</td>
      <td>Heikkinen, Miss. Laina</td>
      <td>female</td>
      <td>26</td>
      <td>0</td>
      <td>0</td>
      <td>STON/O2. 3101282</td>
      <td>7.925</td>
      <td>NaN</td>
      <td>S</td>
    </tr>
    <tr>
      <td>5</td>
      <td>5</td>
      <td>0</td>
      <td>3</td>
      <td>Allen, Mr. William Henry</td>
      <td>male</td>
      <td>35</td>
      <td>0</td>
      <td>0</td>
      <td>373450</td>
      <td>8.05</td>
      <td>NaN</td>
      <td>S</td>
    </tr>
  </tbody>
</table>

## 📄 License

This dataset does not appear to have a specific license or formal usage agreement provided by its creators or maintainers.  
Users are encouraged to verify usage terms if needed.

## ©️ Credit

Visit [**Kaggle**](https://www.kaggle.com/competitions/titanic) for more information.
