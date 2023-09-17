# Predicting-Mudslides

The purpose of this repository is to showcase various a novel method of prediciting mudslides.

**Performace**

| Method | 2D Modeling | Mohr-Coulomb | Novel Method |
| ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| Montecito, California | 1.07 | 1.41 | 1.21 |
| Collbran, Colorado | 1.23 | 1.37 | 1.29 |
| Oso, Washington | 1.47 | 1.82 | 1.62 |
| La Conchita, California | 1.02 | 1.25 | 1.13 |

Closer the Factor of Safety is to 1 the better the method performed.

Usage
-------------------------------------------------------
The main model is stored in Final.R. In each folder there is a folder specifying the output of the novel method and the output of the 2D modeling method.  

Version
-------------------------
This was all written in R.

Conclusion and Further Research
----------------------
The 2D modeling performed best, followed by the novel method, and then the Mohr-Coulomb method. However, the time to analyze the slopes with the 2D modeling technique for exceeds the nearly instantaneous following methods. A combination should be used for efficient predictions.
