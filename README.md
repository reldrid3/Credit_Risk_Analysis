# Credit Risk Analysis
Columbia Bootcamp Supervised Machine Learning Module

## Random Number Generation
Some of the values for the analyses are slightly different from the starter-code snippets.  This is likely due to different versions of *sklearn* or *imblearn* using slightly different algorithms, despite the same random seed.  The values are still close enough to provide similar results.

## Deliverable #1
This deliverable requested the statistical results from three algorithms: RandomOverSampler, SMOTE, and ClusterCentroids.

| Algorithm | Accuracy Score | Confusion Table/Matrix | Precision/Recall Table |
| --------- | -------------- | --------------- | ---------------------- |
| RandomOverSampler | 0.67 | <table> <tbody>  <tr>  <td>57</td>  <td>30</td>  </tr>  <tr>  <td>5537</td>  <td>11581</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.01</code></td>  <td>0.66</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.68</td>  </tr>  </tbody>  </table> |
| SMOTE | 0.644 | <table> <tbody>  <tr>  <td>54</td>  <td>33</td>  </tr>  <tr>  <td>5691</td>  <td>11427</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.01</code></td>  <td>0.62</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.67</td>  </tr>  </tbody>  </table> |
| ClusterCentroids | | <table> <tbody>  <tr>  <td>51</td>  <td>36</td>  </tr>  <tr>  <td>9681</td>  <td>7437</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.01</code></td>  <td>0.59</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.43</td>  </tr>  </tbody>  </table> |

### Screenshots:
#### RandomOverSampler
![](Screenshots/RandomOverSampler.png)

#### SMOTE
![](Screenshots/SMOTE.png)

#### ClusterCentroids
![](Screenshots/ClusterCentroids.png)

## Deliverable #2

## Deliverable #3

## Deliverable #4
