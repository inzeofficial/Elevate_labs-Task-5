# Elevate_labs-Task-5
Objective: To explore the dataset using Pandas for data manipulation, Seaborn and Matplotlib for visualizations, and identify trends such as survival rates by age, fare, class, and other variables.
Key Sections in the Notebook:

Data Loading and Summary Statistics:

Loads the dataset using Pandas.
Displays data info (e.g., data types, missing values) with df.info().
Provides descriptive statistics with df.describe(include='all').
Counts categorical variables (Sex, Pclass, Embarked) using value_counts() to show distributions (e.g., more males than females, majority in 3rd class).


Pairplot and Correlation Heatmap:

Generates a pairplot for features like Age, Fare, Pclass, and Survived, colored by survival status, to visualize pairwise relationships and distributions.
Creates a correlation heatmap for numeric columns (PassengerId, Survived, Pclass, Age, SibSp, Parch, Fare) using Seaborn, highlighting relationships (e.g., negative correlation between Pclass and Survival).
Histograms:

Plots histograms for Age, Fare, SibSp, and Parch to show distributions (e.g., Age is right-skewed, Fare has many low values with outliers).


Boxplots:

Boxplots for Age and Fare grouped by Survived status, revealing differences (e.g., survivors tended to pay higher fares).


Scatter Plot:

Scatter plot of Age vs. Fare, colored by survival (note: there appears to be a label swap in the code—points for Survived==1 are labeled 'Not Survived' and vice versa; this should be corrected for accuracy).
