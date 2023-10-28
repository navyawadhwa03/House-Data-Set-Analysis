# House Price Dataset Analysis README

In this repository, we delve into an in-depth exploration and analysis of the House Price dataset, a prominent dataset in the domains of real estate and predictive modeling. This dataset offers comprehensive insights into various attributes of residential properties and their corresponding sale prices.

## Dataset

The House Price dataset used in this analysis is presented in CSV format and boasts a diverse range of features related to residential properties, in addition to the crucial target variable:

- `Id`: A unique identifier for each property.
- `MSSubClass`: The building class.
- `MSZoning`: The general zoning classification.
- `LotFrontage`: Linear feet of street connected to the property.
- `LotArea`: The lot's size in square feet.
- `Street`: The type of road access.
- `Alley`: The type of alley access.
- `LotShape`: The general shape of the lot.
- `LandContour`: The flatness of the property.
- `Utilities`: The type of utilities available.
- `LotConfig`: The configuration of the lot.
- `LandSlope`: The slope of the property.
- `Neighborhood`: The physical location within Ames city limits.
- `Condition1`: Proximity to various conditions.
- `Condition2`: Proximity to various conditions (if more than one is present).
- `BldgType`: The type of dwelling.
- `HouseStyle`: The style of the dwelling.
- `OverallQual`: The overall material and finish quality.
- `OverallCond`: The overall condition rating.
- `YearBuilt`: The original construction date.
- `YearRemodAdd`: The remodel date (the same as the construction date if no remodeling or additions).
- `RoofStyle`: The type of roof.
- `RoofMatl`: The roof material.
- `Exterior1st`: The exterior covering on the house.
- `Exterior2nd`: The exterior covering on the house (if more than one material).
- `MasVnrType`: The masonry veneer type.
- `MasVnrArea`: The masonry veneer area in square feet.
- `ExterQual`: The exterior material quality.
- `ExterCond`: The present condition of the material on the exterior.
- `Foundation`: The type of foundation.
- `BsmtQual`: The height of the basement.
- `BsmtCond`: The general condition of the basement.
- `BsmtExposure`: The walkout or garden level basement walls.
- `BsmtFinType1`: The quality of the basement finished area.
- `BsmtFinSF1`: The type 1 finished square feet.
- `BsmtFinType2`: The quality of the second finished area (if present).
- `BsmtFinSF2`: The type 2 finished square feet.
- `BsmtUnfSF`: The unfinished square feet of the basement area.
- `TotalBsmtSF`: The total square feet of basement area.
- `Heating`: The type of heating.
- `HeatingQC`: The heating quality and condition.
- `CentralAir`: Central air conditioning.
- `Electrical`: The electrical system.
- `1stFlrSF`: The square feet of the first floor.
- `2ndFlrSF`: The square feet of the second floor.
- `LowQualFinSF`: The square feet of low-quality finished space (across all floors).
- `GrLivArea`: The above-grade (ground) living area square feet.
- `BsmtFullBath`: The number of basement full bathrooms.
- `BsmtHalfBath`: The number of basement half bathrooms.
- `FullBath`: The number of full bathrooms above grade.
- `HalfBath`: The number of half baths above grade.
- `Bedroom`: The number of bedrooms above the basement level.
- `Kitchen`: The number of kitchens.
- `KitchenQual`: The quality of the kitchen.
- `TotRmsAbvGrd`: The total number of rooms above grade (excluding bathrooms).
- `Functional`: The home's functionality rating.
- `Fireplaces`: The number of fireplaces.
- `FireplaceQu`: The quality of the fireplace.
- `GarageType`: The garage's location.
- `GarageYrBlt`: The year the garage was built.
- `GarageFinish`: The interior finish of the garage.
- `GarageCars`: The size of the garage in car capacity.
- `GarageArea`: The size of the garage in square feet.
- `GarageQual`: The quality of the garage.
- `GarageCond`: The condition of the garage.
- `PavedDrive`: The presence of a paved driveway.
- `WoodDeckSF`: The wood deck area in square feet.
- `OpenPorchSF`: The open porch area in square feet.
- `EnclosedPorch`: The enclosed porch area in square feet.
- `3SsnPorch`: The three-season porch area in square feet.
- `ScreenPorch`: The screen porch area in square feet.
- `PoolArea`: The pool area in square feet.
- `PoolQC`: The quality of the pool.
- `Fence`: The quality of the fence.
- `MiscFeature`: Miscellaneous features not covered in other categories.
- `MiscVal`: The value of miscellaneous features.
- `MoSold`: The month of sale.
- `YrSold`: The year of sale.
- `SaleType`: The type of sale.
- `SaleCondition`: The condition of the sale.
- `SalePrice`: The sale price of the property (our target variable).

## Analysis

This repository offers Jupyter notebooks that serve as your guiding light through a comprehensive analysis of the House Price dataset. The analysis is segmented into the following sections:

1. Determine if the sale price of a house is affected by style of house.
2. Determine if the year of remodelling has any effect on the sale price of the house.
3. Determine if the sale price of the house varies with Land Contour.
4. Determine if the sale price of the house is affected by number of full bathrooms.
5. Determine if the garage area changes with the year the garage was built.
6. Determine the trend of house sale over the years.

## Result

You can check the summary and results in documents folder.
