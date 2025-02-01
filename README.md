# Insurance
# Analyse de Données et Prédiction (


analyse des données et prédiction des charges d'assurance de client d'une société assurance vie en fonction de l'âge , le nombre d'enfant , le bim et d'autre paramètres telle que le fait qu'il soient non fumeur ou pas etc...

## Chargement et comprehension du Dataset

le dataet <a href="Data\Insurance-data.xlsx">Insurance-data.xlsx</a> contient 1000 ligne(observation) & 7 colonnes (variables)
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>age</th>
      <th>sex</th>
      <th>bmi</th>
      <th>children</th>
      <th>smoker</th>
      <th>region</th>
      <th>charges</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>19</td>
      <td>female</td>
      <td>27.900</td>
      <td>0</td>
      <td>yes</td>
      <td>southwest</td>
      <td>16884.92400</td>
    </tr>
    <tr>
      <th>1</th>
      <td>18</td>
      <td>male</td>
      <td>33.770</td>
      <td>1</td>
      <td>no</td>
      <td>southeast</td>
      <td>1725.55230</td>
    </tr>
    <tr>
      <th>2</th>
      <td>28</td>
      <td>male</td>
      <td>33.000</td>
      <td>3</td>
      <td>no</td>
      <td>southeast</td>
      <td>4449.46200</td>
    </tr>
    <tr>
      <th>3</th>
      <td>33</td>
      <td>male</td>
      <td>22.705</td>
      <td>0</td>
      <td>no</td>
      <td>northwest</td>
      <td>21984.47061</td>
    </tr>
    <tr>
      <th>4</th>
      <td>32</td>
      <td>male</td>
      <td>28.880</td>
      <td>0</td>
      <td>no</td>
      <td>northwest</td>
      <td>3866.85520</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>995</th>
      <td>39</td>
      <td>female</td>
      <td>23.275</td>
      <td>3</td>
      <td>no</td>
      <td>northeast</td>
      <td>7986.47525</td>
    </tr>
    <tr>
      <th>996</th>
      <td>39</td>
      <td>female</td>
      <td>34.100</td>
      <td>3</td>
      <td>no</td>
      <td>southwest</td>
      <td>7418.52200</td>
    </tr>
    <tr>
      <th>997</th>
      <td>63</td>
      <td>female</td>
      <td>36.850</td>
      <td>0</td>
      <td>no</td>
      <td>southeast</td>
      <td>13887.96850</td>
    </tr>
    <tr>
      <th>998</th>
      <td>33</td>
      <td>female</td>
      <td>36.290</td>
      <td>3</td>
      <td>no</td>
      <td>northeast</td>
      <td>6551.75010</td>
    </tr>
    <tr>
      <th>999</th>
      <td>61</td>
      <td>female</td>
      <td>29.070</td>
      <td>0</td>
      <td>yes</td>
      <td>northwest</td>
      <td>29141.36030</td>
    </tr>
  </tbody>
</table>
<p>1000 rows × 7 columns</p>
</div>
Le dataset  Fournie des informations essentielles pour comprendre les profils des assurés et les facteurs influençant les coûts des assurances santé.
age : âge de l'individu
sex : sexe de l'individu
bmi : indice de masse corporelle (IMC)
children : nombre d'enfants à charge
smoker : statut de fumeur
region : région de résidence
charges : coûts médicaux facturés

## Prétraitement 

## Modèle


