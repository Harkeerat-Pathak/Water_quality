# Water_Potability

Water potability prediction is a part of supervised machine learning. It involves training a machine learning model on a labeled dataset, where the input features include various water quality parameters and the output label is whether the water is potable or not.

The goal is to develop a model that can accurately predict whether a water sample is potable based on its chemical and physical characteristics. Once the model is trained, it can be used to make predictions on new, unlabeled water samples.

The process typically involves data preprocessing, feature engineering, model selection, and model evaluation. Various machine learning algorithms can be used for this task, such as logistic regression, decision trees, random forests, and support vector machines, among others. The choice of algorithm will depend on the nature of the data and the specific requirements of the application.

## Data Content

#### 1. pH Value: 

The World Health Organization (WHO) recommends that the pH of drinking water should be between 6.5 and 8.5. This pH range is considered safe for consumption and is unlikely to cause any adverse health effects. Water with a pH outside of this range may taste unpleasant or have an unusual odor, and it may also contain harmful substances that can cause illness. For example, water with a very low pH (less than 6.5) may be corrosive and can leach metals from pipes, which can cause health problems if ingested. Water with a very high pH (greater than 8.5) may contain excess levels of minerals such as calcium and magnesium, which can cause health problems if consumed in large amounts over a long period of time. It is important to regularly test the pH of your drinking water to ensure that it falls within the recommended range. If the pH of your water is outside of the recommended range, you may need to take steps to adjust it or find an alternative source of drinking water.

#### 2. Hardness:

Water hardness refers to the amount of dissolved minerals, specifically calcium and magnesium, in the water. Hard water is water that contains a high concentration of these minerals, while soft water has a low concentration of minerals. Hard water is not harmful to drink, but it can cause a variety of problems in household plumbing and appliances. The minerals in hard water can build up in pipes and water heaters, reducing their efficiency and potentially causing them to fail. Hard water can also leave deposits on dishes and laundry, making them appear dingy or spotted. On the other hand, soft water is generally considered to be more desirable for household use because it does not cause these problems. Soft water can also lather more easily with soap, making it more effective for cleaning. The hardness of water can be measured in units called grains per gallon (gpg) or milligrams per liter (mg/L). Water with a hardness of 0 to 3.5 gpg (or 0 to 60 mg/L) is considered to be soft, while water with a hardness of more than 7 gpg (or more than 120 mg/L) is considered to be hard. The appropriate level of water hardness for a household will depend on personal preference and the specific needs of the household.

 #### 3. Solids (Total dissolved solids - TDS):
 
 Total dissolved solids (TDS) refer to the amount of dissolved minerals, salts, and other solid substances in water. These substances can include a variety of ions such as calcium, magnesium, potassium, and sodium, as well as small amounts of organic matter. TDS is typically measured in milligrams per liter (mg/L) or parts per million (ppm). The level of TDS in water can affect its taste, clarity, and overall quality. Water with a high level of TDS may taste salty or have an unusual flavor, and it may also appear cloudy or have a cloudy film on surfaces when it dries. High levels of TDS can also be an indication of the presence of other contaminants in the water.

#### 4. Chloramines:

Chloramines are chemicals that are used to disinfect water and kill harmful bacteria and other pathogens. They are formed when ammonia is added to chlorine, which is commonly used as a disinfectant in water treatment plants. Chloramines are less effective at killing bacteria than chlorine, but they are more stable and longer-lasting, which makes them useful for maintaining a consistent level of disinfection in the water distribution system.

#### 5. Sulfate: 

Sulfate is a type of ion that consists of sulfur and oxygen atoms. It is commonly found in water as a result of the natural breakdown of minerals in rocks and soil. Sulfate is generally considered to be safe for human consumption, and it is not considered to be a health hazard at normal levels.

#### 6. Conductivity: 

Conductivity is the ability of a substance to conduct electricity. In the context of water, conductivity is a measure of the ability of water to conduct electricity and is related to the amount of dissolved ions in the water. These ions can include a variety of substances such as calcium, magnesium, sodium, and potassium.

#### 7. Organic_carbon:

Total Organic Carbon (TOC) in source waters comes from decaying natural organic matter (NOM) as well as synthetic sources. TOC is a measure of the total amount of carbon in organic compounds in pure water. According to US EPA < 2 mg/L as TOC in treated / drinking water, and < 4 mg/Lit in source water which is use for treatment.

#### 8. Trihalomethanes: 

THMs are chemicals which may be found in water treated with chlorine. The concentration of THMs in drinking water varies according to the level of organic material in the water, the amount of chlorine required to treat the water, and the temperature of the water that is being treated. THM levels up to 80 ppm is considered safe in drinking water.

#### 9. Turbidity: 

The turbidity of water depends on the quantity of solid matter present in the suspended state. It is a measure of light emitting properties of water and the test is used to indicate the quality of waste discharge with respect to colloidal matter. The mean turbidity value obtained for Wondo Genet Campus (0.98 NTU) is lower than the WHO recommended value of 5.00 NTU.

#### 10. Potability: 

Indicates if water is safe for human consumption where 1 means Potable and 0 means Not potable.

#### A pyhton code is available. You can download the file

### Happy Learning

