| Date        | Alpha            | L1 Ratio | Features  | Training MSE | Testing MSE | Training R2 Score | Testing R2 Score | Private Score | Public Score |
|-------------|------------------|----------|-----------|-------------|--------------|-------------------|------------------|--------------|---------------|
| March 31 25 | 0.01438449888287663 | 0.01  | 3         | 0.02710     | 0.02877      | 0.00091           | 0.00092          | 0.07615      | 0.06548       |
| March 31 25 | 0.001930697728883249| 0.01  | 3         | 0.02709     | 0.02878      | 0.00100           | 0.00084          | 0.07620      | 0.06550       |
| March 31 25 | 0.01438449888287663 | 0.01  | 4         | 0.02707     | 0.02873      | 0.00206           | 0.00227          | 0.07697      | 0.06584       |
| March 31 25 | 0.001               | 0.01  | 4         | 0.02707     | 0.02875      | 0.00203           | 0.00162          | 0.07637      | 0.06569       |
| March 31 25 | 0.01438449888287663 | 1e-05 | 5         | 0.02707     | 0.02873      | 0.00210           | 0.00226          | 0.07701      | 0.06586       |
| March 31 25 | 0.001               | 0.01  | 5         | 0.02707     | 0.02875      | 0.00203           | 0.00162          | 0.07637      | 0.06569       |
| March 31 25 | 0.01438449888287663 | 1e-07 | 6         | 0.02706     | 0.02874      | 0.00216           | 0.00212          | 0.07702      | 0.06585       |
| April 2 25 | 1.024e-17            | 0.9   | 6         | 0.02706     | 0.02874      | 0.00216           | 0.00211          | 0.07708      | 0.06588       |
| April 2 25 | 1.024e-17            | 0.9   | 8         | 0.02706     | 0.02874      | 0.00220           | 0.00222          | 0.07710      | 0.06588       |
| April 2 25 |0.00019306977288832496| 0.023 | 10        | 0.02706     | 0.02876      | 0.00222           | 0.00133          | 0.07797      | 0.06680       |
| April 2 25 | 1.024e-17            | 0.9   | 12        | 0.02706     | 0.02876      | 0.00224           | 0.00145          | 0.07812      | 0.06692       |
| April 2 25 | 0.0003727593720314938| 0.12  | 12        | 0.02706     | 0.02876      | 0.00224           | 0.00145          | 0.07799      | 0.06680       |
| April 3 25 | 0.001                | 0.01  | 3         | 0.02710     | 0.02878      | 0.00100           | 0.00060          | 0.07620      | 0.06548       |

ADDED LOCATION CLUSTER:
| Date        | Alpha            | L1 Ratio | Features  | Training MSE | Testing MSE | Training R2 Score | Testing R2 Score | Private Score | Public Score | Notes |
|-------------|------------------|----------|-----------|-------------|--------------|-------------------|------------------|--------------|---------------|-------|
| April 8 25  | 0.00193069772888 | 0.01     | 4         | 0.02653     | 0.03093      | 0.00087           | 0.00099          | 0.07617      | 0.06545       | Added location cluster |
| April 8 25  | 0.00037275937203 | 0.78     | 4         | 0.00797     | 0.00810      | 0.00187           | 0.00141          | 0.07618      | 0.06529       | Removed outliers with 3 std |
| April 8 25  | 0.00037275937203 | 0.78     | 4         | 0.00797     | 0.00810      | 0.00191           | 0.00139          | 0.07618      | 0.06529       | Changed num clusters to 70 |
| April 8 25  | 0.00037275937203 | 1.00     | 4         | 0.00800     | 0.00787      | 0.00172           | 0.00197          | 0.07615      | 0.06527       | Changed std to 5 |
| April 8 25  | 0.00138949549437 | 0.01     | 4         | 0.01284     | 0.01351      | 0.00129           | 0.00206          | 0.07611      | 0.06528       | Changed std to 6 |

 

Feature Importance:
3 Features: ['bedroomcnt', 'taxvaluedollarcnt', 'lotsizesquarefeet']
4 Features: ['bedroomcnt', 'taxvaluedollarcnt', 'lotsizesquarefeet', 'calculatedfinishedsquarefeet']
5 Features: ['bedroomcnt', 'taxvaluedollarcnt', 'lotsizesquarefeet', 'calculatedfinishedsquarefeet', 'bathroomcnt']
6 Features: ['bedroomcnt', 'taxvaluedollarcnt', 'lotsizesquarefeet', 'calculatedfinishedsquarefeet', 'bathroomcnt', 'yearbuilt']
8 Features: ['bedroomcnt', 'taxvaluedollarcnt', 'lotsizesquarefeet', 'calculatedfinishedsquarefeet', 'bathroomcnt', 'yearbuilt', 'latitude', 'longitude']
important_features = [
    'latitude', 'longitude', 'lotsizesquarefeet', 'calculatedfinishedsquarefeet',
    'finishedsquarefeet12', 'finishedsquarefeet13', 'finishedsquarefeet15',
    'finishedsquarefeet50', 'finishedsquarefeet6',
    'bathroomcnt', 'bedroomcnt', 'yearbuilt']




