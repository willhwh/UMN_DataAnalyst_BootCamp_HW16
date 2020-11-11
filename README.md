# UMN_DataAnalyst_BootCamp_HW16
<ul>
    <li>
    How to select the features:<br>
    Since this project is a classification type question, I decided to use a Tree Based Classifier
    <strong>ExtraTreesClassifier</strong> to get the <strong> top important/relevant scroe </strong>for each feature.
        Feature Importance:
    </li>
    <li>
    The algorithms:<br>
    To deal with a classification type question, classifier algorithms below are used:
        <ol>
            <li>
            Normal Neural Network
            </li>
            <li>
            Mutiple Layers Neural Network
            </li>
            <li>
            Logistic Regression Classifier
            </li>
            <li>
            K-Nearest Neighbor Classifier
            </li>
            <li>
            Decision Tree Classifier
            </li>
            <li>
            Random Forest Classifier
            </li>
        </ol>
    </li>
    <li>
    Result datafram is shown in the jupyter notebook for refference.
    </li>
    <li>
    Random Forest Classifier is the one I chose to do further tuning for the fact that it has the best accuracy.
    </li>
    <li>
    The best parameter combination for Random Forest Classifier is {'class_weight': 'balanced',<br> 'criterion': 'gini',<br> 'max_depth': 9,<br> 'max_features': 'log2',<br> 'min_samples_split': 2,<br> 'n_estimators': 50,<br> 'n_jobs': 1}
    </li>
    <li>
    The accuracy based on test set is: 0.8855
    </li>
</ul>
