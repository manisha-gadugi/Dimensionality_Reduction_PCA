# Dimensionality_Reduction_PCA
Reduce Data Dimensionality for the House Dataset Attribute


# Problem Statement:
When the number of features is very large relative to the number of observations in your dataset, certain algorithms struggle to train effective models. Dimensionality reduction is the process of reducing the number of random variables under consideration, by obtaining a set of principal variables. 
Using principal component analysis, reduce the data dimensions for the housing data attributes. 

# Data Description: 
•	Zoning_Class: Identifies the general zoning classification of the sale 
•	Building_Class: Identifies the type of dwelling involved in the sale 
•	Lot_Extent: Linear feet of street connected to property 
•	Lot_Size: Lot size in square feet 
•	Road_Type: Type of road access to property 
•	Lane_Type: Type of alley access to property 
•	Property_Shape: General shape of property 
•	Land_Outline: Flatness of the property 
•	Utility_Type: Type of utilities available 
•	Lot configuration: Lot configuration 
•	Property_Slope: Slope of property 
•	Neighborhood: Physical locations within Ames city limits 
•	Condition1: Proximity to various conditions 
•	Condition2: Proximity to various conditions (if more than one is present) 
•	House_Type: Type of dwelling 
•	House_Design: Style of dwelling 
•	Overall_Material: Rates the overall material and finish of the house 
•	House_Condition: Rates the overall condition of the house 
•	Construction_Year: Original construction date 
•	Remodel_Year: Remodel date (same as construction date if no remodeling or additions) 
•	Roof_Design: Type of roof 
•	Roof_Quality: Roof material 
•	Exterior1st: Exterior covering on house 
•	Exterior2nd: Exterior covering on house (if more than one material) 
•	Brick_Veneer_Type: Masonry veneer type 
•	Brick_Veneer_Area: Masonry veneer area in square feet 
•	Exterior_Material: Evaluates the quality of the material on the exterior 
•	Exterior_Condition: Evaluates the present condition of the material on the exterior 
•	Foundation_Type: Type of foundation 
•	Basement_Height: Evaluates the height of the basement 
•	Basement_Condition: Evaluates the general condition of the basement 
•	Exposure_Level: Refers to walkout or garden level walls 
•	BsmtFinType1: Rating of basement finished area 
•	BsmtFinSF1: Type 1 finished square feet 
•	BsmtFinType2: Rating of basement finished area (if multiple types) 
•	BsmtFinSF2: Type 2 finished square feet 
•	BsmtUnfSF: Unfinished square feet of basement area 
•	Total_Basement_Area: Total square feet of basement area 
•	Heating_Type: Type of heating 
•	Heating_Quality: Heating quality and condition 
•	Air_Conditioning: Central air conditioning 
•	Electrical_System: Electrical system 
•	First_Floor_Area: First Floor square feet 
•	Second_Floor_Area: Second floor square feet 
•	LowQualFinSF: Low quality finished square feet (all floors) 
•	Grade_Living_Area: Above grade (ground) living area square feet 
•	Underground_Full_Bathroom: Basement full bathrooms 
•	Underground_Half_Bathroom: Basement half bathrooms 
•	Full_Bathroom_Above_Grade: Full bathrooms above grade 
•	Half_Bathroom_Above_Grade: Half baths above grade 
•	Bedroom: Bedrooms above grade (does NOT include basement bedrooms) 
•	Kitchen: Kitchens above grade 
•	Kitchen_Quality: Kitchen quality 
•	Rooms_Above_Grade: Total rooms above grade (does not include bathrooms) 
•	Functional_Rate: Home functionality (Assume typical unless deductions are warranted) 
•	Fireplaces: Number of fireplaces 
•	Fireplace_Quality: quality of fireplaces 
•	Garage: Garage location 
•	Garage_Built_Year: Year garage was built 
•	Garage_Finish_Year: Interior finish of the garage 
•	Garage_Size: Size of garage in car capacity 
•	Garage_Area: Size of garage in square feet 
•	Garage_Quality: Garage quality 
•	Garage_Condition: Garage condition 
•	Pavedd_Drive: Paved driveway 
•	W_Deck_Area: Wood deck area in square feet 
•	Open_Lobby_Area: Open porch area in square feet 
•	Enclosed_Lobby_Area: Enclosed porch area in square feet 
•	Three_Season_Lobby_Area: Three season porch area in square feet 
•	Screen_Lobby_Area: Screen porch area in square feet 
•	Pool_Area: Pool area in square feet 
•	Pool_Quality: Pool quality 
•	Fence_Quality: quality of fence 
•	Miscellaneous_Feature: Miscellaneous feature not covered in other categories 
•	Miscellaneous_Value: $Value of miscellaneous feature 
•	Month_Sold: Month Sold (MM) 
•	Year_Sold: Year Sold (YYYY) 
•	Sale_Type: Type of sale 
•	Sale_Condition: Condition of sale 

Evaluation Parameters 
Evaluation will be based on: 
Data transformation: Normalize or Standardize the data. 

Expected Outcome 
Reduction in number of components based on the hyperparameter set.
