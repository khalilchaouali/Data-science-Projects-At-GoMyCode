# Cp-meter
Reproducing classical machine learning model for predicting the heat capacity of solid inorganics based on Anthony Wang  BestPractices repository.

Overview:

Heat capacity is a very important thermodynamic property. This property represents the amount of thermal energy required to raise the temperature by a unit of temperature. Calorimetry is the process of measuring heat into and out of systems. As you may think, heat capacity is an essential measurement used in many fields of science and engineering. Tables representing heat capacities of different materials is included in almost every fundamental engineering books.
 
The research paper consider using a machine learning model for predicting heat capacity for solid inorganics, thus considering ML models to replace experimental measurement which can be costly and expensive. This paper proves that ML model gives higher accuracy compared to the existing methods such as Neuman-kopp, using mixed-exode constituents, cation/anion contribution (CAC)...

To summarize, this machine learning model is very simple and does only require chemical formula as an input. Using CBFV package or "composition-based feature vectors" which require the chemical formula as input and based on the formula, the outputs will be 177 features representing the thermochemical/thermophysical properties.
 
This is a simple reproducing of some of the models used in the research paper.
