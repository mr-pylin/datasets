# 🗃️ Car Evaluation Dataset

- Car Evaluation Database was derived from a simple hierarchical decision model.
- **Number of Instances:** 1728
- **Reference Paper**:
  - [**DEX: An Expert System Shell for Decision Support**](http://www-ai.ijs.si/MarkoBohanec/pub/Sistemica90.pdf) by [*Marko Bohanec*](https://scholar.google.fr/citations?user=USKxp9IAAAAJ&hl=en) et al. in 1990.
- **Creator**:
  - [Marko Bohanec](https://scholar.google.fr/citations?user=USKxp9IAAAAJ&hl=en)

## 🔍 More Details

<table style="margin:0 auto; border: 1px solid;">
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
      <td>buying</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>Buying price</td>
    </tr>
    <tr>
      <td>1</td>
      <td>maint</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>Price of the maintenance</td>
    </tr>
    <tr>
      <td>2</td>
      <td>doors</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>Number of doors</td>
    </tr>
    <tr>
      <td>3</td>
      <td>persons</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>Capacity in terms of persons to carry</td>
    </tr>
    <tr>
      <td>4</td>
      <td>lug_boot</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>The size of luggage boot</td>
    </tr>
    <tr>
      <td>5</td>
      <td>safety</td>
      <td>Feature</td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>Estimated safety of the car</td>
    </tr>
    <tr>
      <td>6</td>
      <td>class</td>
      <td><strong>Target</strong></td>
      <td>Categorical</td>
      <td>N/A</td>
      <td>false</td>
      <td>Evaulation level (unacceptable, acceptable, good, very good)</td>
    </tr>
  </tbody>
</table>

### 🔍 Categorical Attributes

<table style="margin:0 auto; border: 1px solid;">
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
      <td>0</td>
      <td>buying</td>
      <td>4</td>
      <td>vhigh, high, med, low</td>
    </tr>
    <tr>
      <td>1</td>
      <td>maint</td>
      <td>4</td>
      <td>vhigh, high, med, low</td>
    </tr>
    <tr>
      <td>2</td>
      <td>doors</td>
      <td>4</td>
      <td>2, 3, 4, 5more</td>
    </tr>
    <tr>
      <td>3</td>
      <td>persons</td>
      <td>3</td>
      <td>2, 4, more</td>
    </tr>
    <tr>
      <td>4</td>
      <td>lug_boot</td>
      <td>3</td>
      <td>small, med, big</td>
    </tr>
    <tr>
      <td>5</td>
      <td>safety</td>
      <td>3</td>
      <td>low, med, high</td>
    </tr>
    <tr>
      <td>6</td>
      <td>class</td>
      <td>4</td>
      <td>unacc, acc, vgood, good</td>
    </tr>
  </tbody>
</table>

## 🔍 Some Samples

<table style="margin:0 auto; border: 1px solid;">
  <thead>
    <tr>
      <th style="text-align: center;"># Sample</th>
      <th style="text-align: center;">buying</th>
      <th style="text-align: center;">maint</th>
      <th style="text-align: center;">doors</th>
      <th style="text-align: center;">persons</th>
      <th style="text-align: center;">lug_boot</th>
      <th style="text-align: center;">safety</th>
      <th style="text-align: center;">class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>vhigh</td>
      <td>vhigh</td>
      <td>2</td>
      <td>2</td>
      <td>small</td>
      <td>low</td>
      <td>unacc</td>
    </tr>
    <tr>
      <td>227</td>
      <td>vhigh</td>
      <td>med</td>
      <td>2</td>
      <td>4</td>
      <td>small</td>
      <td>high</td>
      <td>acc</td>
    </tr>
    <tr>
      <td>1511</td>
      <td>low</td>
      <td>high</td>
      <td>5more</td>
      <td>more</td>
      <td>big</td>
      <td>high</td>
      <td>vgood</td>
    </tr>
    <tr>
      <td>1526</td>
      <td>low</td>
      <td>med</td>
      <td>2</td>
      <td>4</td>
      <td>med</td>
      <td>high</td>
      <td>good</td>
    </tr>
  </tbody>
</table>

## 📄 License

This dataset is licensed under the [**Creative Commons Attribution 4.0 International (CC BY 4.0)**](https://creativecommons.org/licenses/by/4.0/legalcode) license.  
**TL;DR:** You are free to share and adapt this dataset for any purpose, as long as appropriate credit is given to the original source.

## ©️ Credit

Visit [**UC Irvine Machine Learning Repository**](https://archive.ics.uci.edu/dataset/19/car+evaluation) for more information.
