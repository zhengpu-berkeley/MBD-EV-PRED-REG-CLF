
Evaluated by Cross Validation RMSE:

    Target:         log(MBD)
    Covariates:     Decorr + Feature Selection

                Model                  CV-RMSE               TEST     
    Baseline y_bar              :       0.777       :       0.758
    OLS + Forward Selection     :       0.429       :       0.404
    OLS + Bidirectional         :       0.425       :       0.399   
    Lasso                       :       0.436       :       0.394   
    KNN + Forward Selection     :       0.447       :       0.409  
    Decision Tree               :       0.539       :       0.497
    Multi Layer Perceptron      :       0.500       :       0.450
    LightGBM                    :       0.426       :       0.396   
    Random Forest               :       0.440       :       0.406   
    SVM rbf kernel              :       0.426       :       0.381   


