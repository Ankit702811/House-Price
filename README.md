# House-Price
Problem Statement

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model which will help the bank marketing team to
know which customer will buy the product.

Task3:-Suggestions to the Bank market team to make customers buy the
product.

Domain Analysis
* Comparable home values, the age, size, and condition of a property, neighborhood appeal, and the health of the overall housing market can affect home prices.

* The main factor which affects property prices is the supply and demand of that particular area. Properties located in areas with a great deal of good quality development and convenience to all facilities attract buyers from other places, thus pushing up the price.

Atrribute information:

SalePrice: The property's sale price in dollars. This is typically the target variable that you want to predict in a regression analysis.

MSSubClass: The building class. This categorizes the type of dwelling based on its construction type (e.g., one-story, two-story, split-level).

MSZoning: The general zoning classification of the property, which indicates how the land is legally designated for use (e.g., residential, commercial, agricultural).

LotFrontage: Linear feet of street connected to the property, indicating the width of the lot along the street side.

LotArea: Lot size in square feet, which represents the total area of the land that the property occupies.

Street: Type of road access to the property (e.g., paved, gravel).

Alley: Type of alley access to the property, if any (e.g., paved, gravel, no alley access).

LotShape: General shape of the property lot (e.g., regular, irregular), which can affect property layout and potential use.

LandContour: Flatness of the property (e.g., level, banked, gentle slope), which can influence construction feasibility and aesthetics.

Utilities: Type of utilities available to the property (e.g., electricity, gas, water, sewer), essential for living conditions and property value.

LotConfig: Lot configuration, describing the position and shape of the property within its surroundings (e.g., inside lot, corner lot).

LandSlope: Slope of the property (e.g., gentle, moderate, severe).

Neighborhood: Physical locations within Ames city limits, which can significantly impact property value and desirability.

Condition1: Proximity to main road or railroad.

Condition2: Proximity to main road or railroad (if a second is present).

BldgType: Type of dwelling (e.g., single-family, townhouse, duplex).

HouseStyle: Style of dwelling (e.g., one-story, two-story).

OverallQual: Overall material and finish quality of the house.

OverallCond: Overall condition rating of the house.

YearBuilt: Original construction date of the house.

YearRemodAdd: Remodel date (if any).

RoofStyle: Type of roof.

RoofMatl: Roof material.

Exterior1st: Exterior covering on the house.

Exterior2nd: Exterior covering on the house (if more than one material).

MasVnrType: Masonry veneer type.

MasVnrArea: Masonry veneer area in square feet.

ExterQual: Exterior material quality.

ExterCond: Present condition of the material on the exterior.

Foundation: Type of foundation.

BsmtQual: Height of the basement.

BsmtCond: General condition of the basement.

BsmtExposure: Walkout or garden level basement walls.

BsmtFinType1: Quality of basement finished area (if present).

BsmtFinSF1: Type 1 finished square feet.

BsmtFinType2: Quality of second finished area (if present).

BsmtFinSF2: Type 2 finished square feet.

BsmtUnfSF: Unfinished square feet of basement area.

TotalBsmtSF: Total square feet of basement area.

Heating: Type of heating.

HeatingQC: Heating quality and condition.

CentralAir: Central air conditioning (Y/N).

Electrical: Electrical system.

1stFlrSF: First floor square feet.

2ndFlrSF: Second floor square feet.

LowQualFinSF: Low quality finished square feet (all floors).

GrLivArea: Above grade (ground) living area square feet.

BsmtFullBath: Basement full bathrooms.

BsmtHalfBath: Basement half bathrooms.

FullBath: Full bathrooms above grade.

HalfBath: Half baths above grade.

Bedroom: Number of bedrooms above basement level.

Kitchen: Number of kitchens.

KitchenQual: Kitchen quality.

TotRmsAbvGrd: Total rooms above grade (does not include bathrooms).

Functional: Home functionality rating.

Fireplaces: Number of fireplaces.

FireplaceQu: Fireplace quality.

GarageType: Garage location.

GarageYrBlt: Year garage was built.

GarageFinish: Interior finish of the garage.

GarageCars: Size of garage in car capacity.

GarageArea: Size of garage in square feet.

GarageQual: Garage quality.

GarageCond: Garage condition.

PavedDrive: Paved driveway (Y/N).

WoodDeckSF: Wood deck area in square feet.

OpenPorchSF: Open porch area in square feet.

EnclosedPorch: Enclosed porch area in square feet.

3SsnPorch: Three season porch area in square feet.

ScreenPorch: Screen porch area in square feet.

PoolArea: Pool area in square feet.

PoolQC: Pool quality.

Fence: Fence quality.

MiscFeature: Miscellaneous feature not covered in other categories.

MiscVal: $Value of miscellaneous feature.

MoSold: Month Sold.

YrSold: Year Sold.

SaleType: Type of sale.

SaleCondition: Condition of sale.

These variables collectively provide a detailed description of various aspects of residential properties, which are crucial for understanding their market value, characteristics, and appeal to potential buyers. In predictive modeling, selecting and appropriately transforming these features can significantly impact the accuracy and usefulness of the models built to predict the sale price or other aspects of real estate transactions.

Conclusion-  Xtream Gradiant Boosting with hyperparameter tunning using randomizes search Cross-Validation is best fit model for this dataset.It                     is giving good accuracy and generalized model.

Report on challenges faced:

* Data preprocessing: Dataset is large, so preprocessing is lengthy.

* Feature Selection: Choosing the right set of features that are relevant to the problem at hand can significantly impact the accuracy of a model.

* Solutions to problems we encountered while working on this project.
