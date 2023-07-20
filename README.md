# Dry-Bean-Classification-

Problem statement The goal of this project is to predict the type of bean using various features of the bean. This is a multi-class classification problem. F1-score is taken as an evaluation metric.
- Dataset The dataset for this assignment is the Dry Bean Dataset. It contains various features of different types of beans, as well as their corresponding type.
- Relevant Information Seven different types of dry beans were used in the research, taking into account the features such as form, shape, type, and structure by the market situation. A computer vision system was
developed to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification. For the classification model, images of 13,611 grains of 7 different registered dry
beans were taken with a high-resolution camera. Bean images obtained by computer vision system were subjected to segmentation and feature extraction stages, and a total of 16 features; 12 dimensions and 4 shape forms,
were obtained from the grains.
- Data description The dataset contains the following features:
Area (A): The area of a bean zone and the number of pixels within its boundaries.
Perimeter (P): Bean circumference is defined as the length of its border.
Major axis length (L): The distance between the ends of the longest line that can be drawn from a bean.
Minor axis length (l): The longest line that can be drawn from the bean while standing perpendicular to the main axis.
Aspect ratio (K): Defines the relationship between L and l.
Eccentricity (Ec): Eccentricity of the ellipse having the same moments as the region.
Convex area (C): Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
Equivalent diameter (Ed): The diameter of a circle having the same area as a bean seed area.
Extent (Ex): The ratio of the pixels in the bounding box to the bean area.
Solidity (S): Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.
Roundness (R): Calculated with the following formula: (4piA)/(P^2)
Compactness (CO): Measures the roundness of an object: Ed/L
ShapeFactor1 (SF1)
ShapeFactor2 (SF2)
ShapeFactor3 (SF3)
ShapeFactor4 (SF4)
Class (the type of bean: Seker, Barbunya, Bombay, Cali, Dermosan, Horoz, and Sira)
NOTE: The Class column is the target variable.
