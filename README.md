# Dry_beans_ML

I obtain the training dataset form the UCI Machine Learning Repository website. For this dataset Seven different types of dry beans were used in this research, taking into account the features such as form, shape, type, and structure by the market situation. A computer vision system was developed to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification. For the classification model, images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. Bean images obtained by computer vision system were subjected to segmentation and feature extraction stages, and a total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains. The 12 dimensions are:

- Area: The area of a bean zone and the number of pixels within its boundaries.

- Perimeter: Bean circumference is defined as the length of its border.

Major axis length: The distance between the ends of the longest line that can be drawn from a bean.

Minor axis length: The longest line that can be drawn from the bean while standing perpendicular to the main axis.

Aspect ratio: Defines the relationship between Major axis length and Minor axis length.

Eccentricity: Eccentricity of the ellipse having the same moments as the region.

Convex area: Number of pixels in the smallest convex polygon that can contain the area of a bean seed.

Equivalent diameter: The diameter of a circle having the same area as a bean seed area.

Extent: The ratio of the pixels in the bounding box to the bean area.

Solidity: The ratio of the pixels in the convex shell to those found in beans.

Roundness: Calculated with the following formula: (4piArea)/(Perimeter^2)

Compactness: Measures the roundness of an object: (Equivalent diameter)/(Major axis length)

Form my data set I know it is a multivariate classification problem where my target is the Class columns which consist of seven different classifications which are “Horoz, Bombay, Dermason, Barbunya, seker, Sira, Cali”.

in this project i used three machine learning model which are Logistic Regression, Random Forest Classifire, and XGBoost
