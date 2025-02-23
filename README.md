# text-similarity-using-pycaret
the dataset used for this documnetation is [text similarity](https://www.kaggle.com/datasets/rishisankineni/text-similarity) from kaggle

## outcome for classification
|index|model|accuracy|AUC|recall|prec\.|F1|kappa|MCC|TT \(sec\)|TOPSIS SCORE|RANK|
|---|---|---|---|---|---|---|---|---|---|---|---|
|ridge|Ridge Classifier|0\.9106|0\.942|0\.9832|0\.9064|0\.9431|0\.7361|0\.7507|0\.113|0\.9118656714675604|1\.0|
|lr|Logistic Regression|0\.9013|0\.9498|0\.9867|0\.8936|0\.9378|0\.7017|0\.7234|0\.105|0\.8974539877128694|2\.0|
|lda|Linear Discriminant Analysis|0\.9079|0\.8878|0\.9734|0\.9109|0\.941|0\.7326|0\.7424|0\.08|0\.8954156920767353|3\.0|
|nb|Naive Bayes|0\.9186|0\.9486|0\.9584|0\.9355|0\.9467|0\.7745|0\.7763|0\.094|0\.8874718693103489|4\.0|
|dt|Decision Tree Classifier|0\.9073|0\.8267|0\.9858|0\.9007|0\.9413|0\.7231|0\.7413|0\.137|0\.8534178959640282|5\.0|
|ada|Ada Boost Classifier|0\.9093|0\.9074|0\.9832|0\.9047|0\.9423|0\.7321|0\.7468|0\.173|0\.8499292283866678|6\.0|
|xgboost|Extreme Gradient Boosting|0\.9053|0\.9139|0\.9477|0\.9283|0\.9366|0\.7456|0\.7527|0\.163|0\.8155634741560251|7\.0|
|gbc|Gradient Boosting Classifier|0\.9133|0\.9108|0\.9849|0\.9082|0\.9449|0\.7433|0\.7586|0\.216|0\.8126772488447469|8\.0|
|rf|Random Forest Classifier|0\.9146|0\.9354|0\.9885|0\.907|0\.9458|0\.7458|0\.7631|0\.238|0\.7959767222977772|9\.0|
|et|Extra Trees Classifier|0\.9253|0\.945|0\.984|0\.9223|0\.9521|0\.7834|0\.793|0\.335|0\.7185842502747192|10\.0|
|lightgbm|Light Gradient Boosting Machine|0\.9079|0\.9141|0\.9849|0\.902|0\.9416|0\.7262|0\.7432|0\.32|0\.7136106618696306|11\.0|
|qda|Quadratic Discriminant Analysis|0\.8566|0\.8747|0\.8734|0\.932|0\.9009|0\.6414|0\.6482|0\.082|0\.6637366222297288|12\.0|
|dummy|Dummy Classifier|0\.7532|0\.5|1\.0|0\.7532|0\.8592|0\.0|0\.0|0\.077|0\.4240963659377687|13\.0|
|knn|K Neighbors Classifier|0\.7191|0\.5545|0\.9167|0\.7597|0\.8308|0\.0438|0\.0568|0\.099|0\.33329998947930634|14\.0|
|svm|SVM - Linear Kernel|0\.7025|0\.5024|0\.9|0\.6778|0\.7733|0\.0|0\.0|0\.159|0\.21597955271024002|15\.0|
