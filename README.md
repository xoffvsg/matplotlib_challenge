# matplotlib_challenge
## Module 5 Challenge
### Pymaceuticals, inc.


Nine drugs (Capomulin, Ketapril, Naftisol, Infubinol, Stelasyn, Ramicane, Zoniferol, Propriva, and Ceftamin) and a placebo were tested on 248 mice over a period of 45 days. The changes in the volume of the tumors were recorded at regular interval through the experiment.
The gender of the mice in the dataset was equally distributed between male and female (respectively 51.0% and 49.0%)
</br>

![image](https://github.com/xoffvsg/matplotlib_challenge/assets/141395221/4be3932b-4293-46b7-86f2-2d81e3097518)

</br></br>

The data from the four drugs showing the smallest standard deviations for the tumor volume (Capomulin, Ramicane, Infubinol, and Ceftamin) was investigated further. They also correspond to the drugs giving the smallest mean tumor volume once the drug Propriva was discarded on the basis of its slightly larger standard deviation and smaller sample size.
</br></br>
<div>


<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Mean Tumor Volume</th>
      <th>Median Tumor Volume</th>
      <th>Tumor Volume Variance</th>
      <th>Tumor Volume Std. Dev.</th>
      <th>Tumor Volume Std. Err.</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Capomulin</th>
      <td>40.675741</td>
      <td>41.557809</td>
      <td>24.947764</td>
      <td>4.994774</td>
      <td>0.329346</td>
    </tr>
    <tr>
      <th>Ceftamin</th>
      <td>52.591172</td>
      <td>51.776157</td>
      <td>39.290177</td>
      <td>6.268188</td>
      <td>0.469821</td>
    </tr>
    <tr>
      <th>Infubinol</th>
      <td>52.884795</td>
      <td>51.820584</td>
      <td>43.128684</td>
      <td>6.567243</td>
      <td>0.492236</td>
    </tr>
    <tr>
      <th>Ketapril</th>
      <td>55.235638</td>
      <td>53.698743</td>
      <td>68.553577</td>
      <td>8.279709</td>
      <td>0.603860</td>
    </tr>
    <tr>
      <th>Naftisol</th>
      <td>54.331565</td>
      <td>52.509285</td>
      <td>66.173479</td>
      <td>8.134708</td>
      <td>0.596466</td>
    </tr>
    <tr>
      <th>Placebo</th>
      <td>54.033581</td>
      <td>52.288934</td>
      <td>61.168083</td>
      <td>7.821003</td>
      <td>0.581331</td>
    </tr>
    <tr>
      <th>Propriva</th>
      <td>52.320930</td>
      <td>50.446266</td>
      <td>43.852013</td>
      <td>6.622085</td>
      <td>0.544332</td>
    </tr>
    <tr>
      <th>Ramicane</th>
      <td>40.216745</td>
      <td>40.673236</td>
      <td>23.486704</td>
      <td>4.846308</td>
      <td>0.320955</td>
    </tr>
    <tr>
      <th>Stelasyn</th>
      <td>54.233149</td>
      <td>52.431737</td>
      <td>59.450562</td>
      <td>7.710419</td>
      <td>0.573111</td>
    </tr>
    <tr>
      <th>Zoniferol</th>
      <td>53.236507</td>
      <td>51.818479</td>
      <td>48.533355</td>
      <td>6.966589</td>
      <td>0.516398</td>
    </tr>
  </tbody>
</table>
</div>

</br></br>
The analysis of the distributions of the tumor sizes at the end of the treatment for these four drugs shows that mice treated with Capomulin and Ramicane ended up with smaller tumors than the ones treated with Infubinol and Ceftamin.
</br></br>

![image](https://github.com/xoffvsg/matplotlib_challenge/assets/141395221/7a2d8974-a73c-448c-a5b8-772ce16271a0)

</br></br>

The results for the mice treated with Capomulin show a strong positive correlation between the weight of the mice and the volume of their tumor.
</br></br>
![image](https://github.com/xoffvsg/matplotlib_challenge/assets/141395221/14038bdb-f02b-4a4d-a761-0447639ad3bf)






