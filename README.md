# Credit Risk Analysis
Columbia Bootcamp Supervised Machine Learning Module

## Random Number Generation
Some of the values for the analyses are slightly different from the starter-code snippets.  This is likely due to different versions of *sklearn* or *imblearn* using slightly different algorithms, despite the same random seed.  The values are still close enough to provide similar results.

## Deliverable #1
This deliverable requested the statistical results from three algorithms: RandomOverSampler, SMOTE, and ClusterCentroids.

| Algorithm | Accuracy Score | Confusion Matrix | Precision/Recall Table |
| --------- | -------------- | ---------------- | ---------------------- |
| RandomOverSampler | 0.666 | <table> <tbody>  <tr>  <td>57</td>  <td>30</td>  </tr>  <tr>  <td>5537</td>  <td>11581</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.01</code></td>  <td>0.66</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.68</td>  </tr>  </tbody>  </table> |
| SMOTE | 0.644 | <table> <tbody>  <tr>  <td>54</td>  <td>33</td>  </tr>  <tr>  <td>5691</td>  <td>11427</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.01</code></td>  <td>0.62</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.67</td>  </tr>  </tbody>  </table> |
| ClusterCentroids | 0.510 | <table> <tbody>  <tr>  <td>51</td>  <td>36</td>  </tr>  <tr>  <td>9681</td>  <td>7437</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.01</code></td>  <td>0.59</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.43</td>  </tr>  </tbody>  </table> |

### Screenshots:
#### RandomOverSampler
![](Screenshots/RandomOverSampler.png)

#### SMOTE
![](Screenshots/SMOTE.png)

#### ClusterCentroids
![](Screenshots/ClusterCentroids.png)

## Deliverable #2
This deliverable requested the statistical results from one algorithm: SMOTEENN.

| Algorithm | Accuracy Score | Confusion Matrix | Precision/Recall Table |
| --------- | -------------- | ---------------- | ---------------------- |
| SMOTEENN | 0.638 | <table> <tbody>  <tr>  <td>57</td>  <td>30</td>  </tr>  <tr>  <td>5537</td>  <td>11581</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.01</code></td>  <td>0.66</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.68</td>  </tr>  </tbody>  </table> |

### Screenshot:
#### SMOTEENN
![](Screenshots/SMOTEENN.png)

## Deliverable #3
This deliverable requested the statistical results from two algorithms: BalancedRandomForestClassifier and EasyEnsembleClassifier.

| Algorithm | Accuracy Score | Confusion Matrix | Precision/Recall Table |
| --------- | -------------- | ---------------- | ---------------------- |
| BalancedRandomForestClassifier | 0.787 | <table> <tbody>  <tr>  <td>58</td>  <td>29</td>  </tr>  <tr>  <td>1582</td>  <td>15536</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.04</code></td>  <td>0.67</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.91</td>  </tr>  </tbody>  </table> |
| EasyEnsembleClassifier | 0.925 | <table> <tbody>  <tr>  <td>79</td>  <td>8</td>  </tr>  <tr>  <td>978</td>  <td>16140</td>  </tr>  </tbody>  </table> | <table>  <thead>  <tr>  <th></th>  <th>Precision</th>  <th>Recall</th>  </tr>  </thead>  <tbody>  <tr>  <td>high_risk</td>  <td>0.07</code></td>  <td>0.91</td>  </tr>  <tr>  <td>low_risk</td>  <td>1.00</td>  <td>0.94</td>  </tr>  </tbody>  </table> |

### Screenshots:
#### BalancedRandomForestClassifier
![](Screenshots/BalancedRandomForestClassifier.png)

#### EasyEnsembleClassifier
![](Screenshots/EasyEnsembleClassifier.png)


## Deliverable #4
