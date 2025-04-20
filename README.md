# DiamondsLinearRegression

Проект за предвидување на цената на дијамантите користејќи линеарна регресија.

Овој проект користи линеарна регресија и нејзини варијации (Ridge, Lasso, ElasticNet, Bayesian Ridge) за предвидување на цената на дијаманти врз основа на нивните карактеристики.

Извор:[Kaggle Diamonds Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds)
-Вклучува информации за carat, cut, color, clarity и цена (price).

Методи кои се користени:
- One-hot encoding
- Standard scaling
- LinearRegression, Ridge, Lasso, ElasticNet, BayesianRidge
- Мерки: R², MAE, MSE

Добиени резултати:
Модел:        | R² score
Linear        | 0.9075
Ridge         | 0.9070     
Lasso         | 0.9073
ElasticNet    | 0.9075  
BayesianRidge | 0.9074   


