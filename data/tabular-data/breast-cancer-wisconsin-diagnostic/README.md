# 🗃️ Breast Cancer Wisconsin (Diagnostic) Dataset
   - Diagnostic Wisconsin Breast Cancer Database.
   - **Number of Instances:** 569
   - **Reference Paper**:
      - [**Breast Cancer Diagnosis and Prognosis via Linear Programming**](https://minds.wisconsin.edu/handle/1793/64370) by [*William Wolberg*](https://scholar.google.com/citations?user=R-kw9JYAAAAJ&hl=en) et al. in 1994.  
   - **Creators**:
      - [William Wolberg](https://scholar.google.com/citations?user=R-kw9JYAAAAJ&hl=en)
      - [Olvi Mangasarian](https://scholar.google.com/citations?user=OkJ1G8YAAAAJ&hl=en)
      - [Nick Street](https://scholar.google.com/citations?user=-kKtBb8AAAAJ&hl=en)
      - [W. Street](https://https://unknown.org)

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
         <td>ID</td>
         <td>Identifier</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>Unique identifier for each patient</td>
      </tr>
      <tr>
         <td>1</td>
         <td>Diagnosis</td>
         <td><strong>Target</strong></td>
         <td>Categorical</td>
         <td>N/A</td>
         <td>false</td>
         <td>Diagnosis of breast tissues (M = malignant, B = benign)</td>
      </tr>
      <tr>
         <td>2</td>
         <td>radius1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm</td>
         <td>false</td>
         <td>distance from center to points on the perimeter</td>
      </tr>
      <tr>
         <td>3</td>
         <td>texture1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>standard deviation of gray-scale values</td>
      </tr>
      <tr>
         <td>4</td>
         <td>perimeter1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>5</td>
         <td>area1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm²</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>6</td>
         <td>smoothness1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>local variation in radius lengths</td>
      </tr>
      <tr>
         <td>7</td>
         <td>compactness1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>perimeter^2 / area - 1.0</td>
      </tr>
      <tr>
         <td>8</td>
         <td>concavity1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>severity of concave portions of the contour</td>
      </tr>
      <tr>
         <td>9</td>
         <td>concave_points1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>number of concave portions of the contour</td>
      </tr>
      <tr>
         <td>10</td>
         <td>symmetry1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>11</td>
         <td>fractal_dimension1</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>"coastline approximation" - 1</td>
      </tr>
         <td>12</td>
         <td>radius2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm</td>
         <td>false</td>
         <td>distance from center to points on the perimeter</td>
      </tr>
      <tr>
         <td>13</td>
         <td>texture2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>standard deviation of gray-scale values</td>
      </tr>
      <tr>
         <td>14</td>
         <td>perimeter2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>15</td>
         <td>area2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm²</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>16</td>
         <td>smoothness2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>local variation in radius lengths</td>
      </tr>
      <tr>
         <td>17</td>
         <td>compactness2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>perimeter^2 / area - 1.0</td>
      </tr>
      <tr>
         <td>18</td>
         <td>concavity2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>severity of concave portions of the contour</td>
      </tr>
      <tr>
         <td>19</td>
         <td>concave_points2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>number of concave portions of the contour</td>
      </tr>
      <tr>
         <td>20</td>
         <td>symmetry2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>21</td>
         <td>fractal_dimension2</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>"coastline approximation" - 1</td>
      </tr>
         <td>22</td>
         <td>radius3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm</td>
         <td>false</td>
         <td>distance from center to points on the perimeter</td>
      </tr>
      <tr>
         <td>23</td>
         <td>texture3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>standard deviation of gray-scale values</td>
      </tr>
      <tr>
         <td>24</td>
         <td>perimeter3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>25</td>
         <td>area3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>mm²</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>26</td>
         <td>smoothness3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>local variation in radius lengths</td>
      </tr>
      <tr>
         <td>27</td>
         <td>compactness3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>perimeter^2 / area - 1.0</td>
      </tr>
      <tr>
         <td>28</td>
         <td>concavity3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>severity of concave portions of the contour</td>
      </tr>
      <tr>
         <td>29</td>
         <td>concave_points3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>number of concave portions of the contour</td>
      </tr>
      <tr>
         <td>30</td>
         <td>symmetry3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>N/A</td>
      </tr>
      <tr>
         <td>31</td>
         <td>fractal_dimension3</td>
         <td>Feature</td>
         <td>Numerical</td>
         <td>N/A</td>
         <td>false</td>
         <td>"coastline approximation" - 1</td>
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
         <td>Diagnosis</td>
         <td>2</td>
         <td>M = malignant, B = benign</td>
      </tr>
   </tbody>
</table>

## 🔍 Some Samples
<table style="margin: 0 auto;">
   <thead>
      <tr>
         <th style="text-align: center;"># Sample</th>
         <th style="text-align: center;">ID</th>
         <th style="text-align: center;">Diagnosis</th>
         <th style="text-align: center;">radius1</th>
         <th style="text-align: center;">texture1</th>
         <th style="text-align: center;">perimeter1</th>
         <th style="text-align: center;">area1</th>
         <th style="text-align: center;">smoothness1</th>
         <th style="text-align: center;">compactness1</th>
         <th style="text-align: center;">concavity1</th>
         <th style="text-align: center;">concave_points1</th>
         <th style="text-align: center;">symmetry1</th>
         <th style="text-align: center;">fractal_dimension1</th>
         <th style="text-align: center;">radius2</th>
         <th style="text-align: center;">texture2</th>
         <th style="text-align: center;">perimeter2</th>
         <th style="text-align: center;">area2</th>
         <th style="text-align: center;">smoothness2</th>
         <th style="text-align: center;">compactness2</th>
         <th style="text-align: center;">concavity2</th>
         <th style="text-align: center;">concave_points2</th>
         <th style="text-align: center;">symmetry2</th>
         <th style="text-align: center;">fractal_dimension2</th>
         <th style="text-align: center;">radius3</th>
         <th style="text-align: center;">texture3</th>
         <th style="text-align: center;">perimeter3</th>
         <th style="text-align: center;">area3</th>
         <th style="text-align: center;">smoothness3</th>
         <th style="text-align: center;">compactness3</th>
         <th style="text-align: center;">concavity3</th>
         <th style="text-align: center;">concave_points3</th>
         <th style="text-align: center;">symmetry3</th>
         <th style="text-align: center;">fractal_dimension3</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>0</td>
         <td>842302</td>
         <td>M</td>
         <td>17.99</td>
         <td>10.38</td>
         <td>122.8</td>
         <td>1001</td>
         <td>0.1184</td>
         <td>0.2776</td>
         <td>0.3001</td>
         <td>0.1471</td>
         <td>0.2419</td>
         <td>0.07871</td>
         <td>1.095</td>
         <td>0.9053</td>
         <td>8.589</td>
         <td>153.4</td>
         <td>0.006399</td>
         <td>0.04904</td>
         <td>0.05373</td>
         <td>0.01587</td>
         <td>0.03003</td>
         <td>0.006193</td>
         <td>25.38</td>
         <td>17.33</td>
         <td>184.6</td>
         <td>2019</td>
         <td>0.1622</td>
         <td>0.6656</td>
         <td>0.7119</td>
         <td>0.2654</td>
         <td>0.4601</td>
         <td>0.1189</td>
      </tr>
      <tr>
         <td>1</td>
         <td>842517</td>
         <td>M</td>
         <td>20.57</td>
         <td>17.77</td>
         <td>132.9</td>
         <td>1326</td>
         <td>0.08474</td>
         <td>0.07864</td>
         <td>0.0869</td>
         <td>0.07017</td>
         <td>0.1812</td>
         <td>0.05667</td>
         <td>0.5435</td>
         <td>0.7339</td>
         <td>3.398</td>
         <td>74.08</td>
         <td>0.005225</td>
         <td>0.01308</td>
         <td>0.0186</td>
         <td>0.0134</td>
         <td>0.01389</td>
         <td>0.003532</td>
         <td>24.99</td>
         <td>23.41</td>
         <td>158.8</td>
         <td>1956</td>
         <td>0.1238</td>
         <td>0.1866</td>
         <td>0.2416</td>
         <td>0.186</td>
         <td>0.275</td>
         <td>0.08902</td>
      </tr>
      <tr>
         <td>19</td>
         <td>8510426</td>
         <td>B</td>
         <td>13.54</td>
         <td>14.36</td>
         <td>87.46</td>
         <td>566.3</td>
         <td>0.09779</td>
         <td>0.08129</td>
         <td>0.06664</td>
         <td>0.04781</td>
         <td>0.1885</td>
         <td>0.05766</td>
         <td>0.2699</td>
         <td>0.7886</td>
         <td>2.058</td>
         <td>23.56</td>
         <td>0.008462</td>
         <td>0.0146</td>
         <td>0.02387</td>
         <td>0.01315</td>
         <td>0.0198</td>
         <td>0.0023</td>
         <td>15.11</td>
         <td>19.26</td>
         <td>99.7</td>
         <td>711.2</td>
         <td>0.144</td>
         <td>0.1773</td>
         <td>0.239</td>
         <td>0.1288</td>
         <td>0.2977</td>
         <td>0.07259</td>
      </tr>
      <tr>
         <td>20</td>
         <td>8510653</td>
         <td>B</td>
         <td>13.08</td>
         <td>15.71</td>
         <td>85.63</td>
         <td>520</td>
         <td>0.1075</td>
         <td>0.127</td>
         <td>0.04568</td>
         <td>0.0311</td>
         <td>0.1967</td>
         <td>0.06811</td>
         <td>0.1852</td>
         <td>0.7477</td>
         <td>1.383</td>
         <td>14.67</td>
         <td>0.004097</td>
         <td>0.01898</td>
         <td>0.01698</td>
         <td>0.00649</td>
         <td>0.01678</td>
         <td>0.002425</td>
         <td>14.5</td>
         <td>20.49</td>
         <td>96.09</td>
         <td>630.5</td>
         <td>0.1312</td>
         <td>0.2776</td>
         <td>0.189</td>
         <td>0.07283</td>
         <td>0.3184</td>
         <td>0.08183</td>
      </tr>
   </tbody>
</table>

# 📄 License
This dataset is licensed under the [**Creative Commons Attribution 4.0 International (CC BY 4.0)**](https://creativecommons.org/licenses/by/4.0/legalcode) license.  
**TL;DR:** You are free to share and adapt this dataset for any purpose, as long as appropriate credit is given to the original source.

# ©️ Credit
Visit [**UC Irvine Machine Learning Repository**](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic) for more information.