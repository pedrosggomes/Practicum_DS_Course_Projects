## Introduction 
Project for Yandex Practicum Course - 2nd Integrated Project for Yandex Practicum Data Science Course
    
## Project Description 


+ **Main goals of the project:**
    + Create a model to help predict the amount of gold recovered from gold ore.
    + The model haves the main goal to optimize the process of production for the company Zyfra, i.e. eliminate unprofitable parameters;


## Description of the data

+ **Technological process**

    + Rougher feed — raw material
    + Rougher additions (or reagent additions) — flotation reagents: Xanthate, Sulphate, Depressant
        + Xanthate — promoter or flotation activator;
        + Sulphate — sodium sulphide for this particular process;
        + Depressant — sodium silicate.
    + Rougher process — flotation
    + Rougher tails — product residues
    + Float banks — flotation unit
    + Cleaner process — purification
    + Rougher Au — rougher gold concentrate
    + Final Au — final gold concentrate

+ **Parameters of stages**

    + air amount — volume of air
    + fluid levels
    + feed size — feed particle size
    + feed rate

## Feature naming: 
    
+ **Possible values for [stage]:**

    + rougher — flotation
    + primary_cleaner — primary purification
    + secondary_cleaner — secondary purification
    + final — final characteristics

+ **Possible values for [parameter_type]:**

    + input — raw material parameters
    + output — product parameters
    + state — parameters characterizing the current state of the stage
    + calculation — calculation characteristics
