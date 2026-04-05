---
title: Home
layout: home
---

**CDE4301 IS-403**

# 1. Introduction (Shannen) 
**1.1. The Rise of Microgreens and Smart Indoor Farming in Singapore**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Singapore imports over 90% of its food due to limited land, making it vulnerable to global supply disruptions. (Singapore Food Agency, 2023) To improve resilience, there is a growing push to increase local food production, particularly through high-efficiency and space-saving methods. (Begum, 2020) Microgreens, which are fast-growing and nutrient-dense, have emerged as a promising way to boost local food supply. (Singh et al., 2024) Indoor farming enables year-round cultivation in controlled environments using methods such as vertical farming and hydroponics, but high operational costs and labour constraints limit large-scale adoption. (Loh, 2024) To address these issues, there is increasing demand for Agriculture 4.0 technologies, including automation, sensors and data-driven systems, which can improve efficiency, optimize resource use and enhance crop quality. (Begum, 2025a) The Singapore Green Plan 2030 was recently postponed to 2035, with renewed plans to support indoor farms and revised targets to increase production of both vegetables and protein. (Begum, 2025b) As the need for fresh, locally grown produce rises (Tham, 2024), integrating advanced technologies into these production methods become essential for achieving sustainable and scalable local food production.


<br> **1.2. Problem Statement**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Duckweed is a fast-growing, nutrient-rich microgreen with potential to contribute to sustainable indoor farming and local food production. (Zięć et al., 2025) However, it is prone to biofilm adhesion, which reduces growth and harms plant health. (Zhang et al., 2010) This presents a key challenge for duckweed cultivation. Addressing biofilm formation and adhesion is therefore critical to ensure healthy duckweed growth and maintain its potential as a sustainable food source. 


<br> **1.3. Project Objectives**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This project aims to develop a system to detect and remove biofilm forming on duckweed in controlled environments. It will begin by evaluating the problem of biofilm on duckweed and current control methods to assess their effectiveness and identify areas for improvement. Based on this, a new method for automated biofilm removal will be designed, and tested, while also considering its impact on duckweed growth. The project will also examine the efficiency and reliability of the system, consider its potential use in intensive duckweed cultivation and provide recommendations for future improvements and applications in sustainable, high-efficiency food production.


# 2. Duckweed (Shannen) 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Duckweed was selected for this project due to its rapid growth, high nutritional content and suitability as a high-efficiency crop in controlled environments. Its rapid doubling time also makes it a practical choice for experiments, as changes in population can be observed over a short period. This section reviews its key characteristics, including physical traits, protein content, clonal reproduction and growth patterns, factors affecting growth and indicators of poor health, providing essential background for addressing challenges such as biofilm formation. 

<br> **2.1. Physical Characteristics**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Duckweed is a small, fast-growing aquatic plant that floats on the surface of freshwater and reproduces primarily through asexual budding, producing genetically identical plants that contribute to rapid colony formation. It is one of the smallest plants, typically 1-15 mm in length, with simple, flat, oval-shaped fronds. (Ziegler et al., 2023) The fronds are buoyant due to air-filled tissues, which help keep the plant afloat (Chen, 2024) and  form dense mats on the water surface. (Walsh et al., 2021) Duckweed naturally grows in still or slow-moving freshwater bodies and can tolerate a range of environmental conditions. (Thingujam et al., 2024) 


<br> **2.2. Nutritional Value**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Duckweed is highly nutritious, containing 20-35g of protein per 100g dry weight. (Appenroth et al., 2017) In comparison, Pak Choi, a locally familiar vegetable, contains about 1.4g of protein per 100g fresh weight, which corresponds to roughly 18g per 100g dry weight. (WebMD, n.d.) Duckweed also doubles its biomass within approximately three days, allowing multiple harvests per week (ScienceDirect, 2016), whereas Pak Choi can typically only be harvested every three weeks. (NParks, 2023) This combination of high protein content and fast growth makes duckweed an attractive option for sustainable indoor food production. Already consumed in countries such as Thailand (Zięć et al., 2025), it demonstrates considerable potential as a future food ingredient. 


<br> **2.3. Clonal Reproduction and Sigmoidal Growth**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Duckweed’s clonal reproduction is closely linked to the classic logistic (sigmoidal) growth model used in population dynamics. (Faizal et al., 2021) Duckweed primarily reproduces through vegetative budding, where a mother frond produces daughter fronds that remain attached briefly before separating. (Zhang et al., 2020) Each new frond is genetically identical, or a clone, and under stable environmental conditions, each frond has roughly the same probability of producing new fronds per unit time. (Ziegler, 2025)

2.3.1. *Lag Phase*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When a new culture is inoculated, there may be a short acclimation period as fronds adjust to the new environment, repair stress and optimize metabolism. (Singh et al., 2025) Population increase is minimal during this phase, which lasts about a day, but fronds are preparing for rapid reproduction.(Faizal et al., 2021) 

2.3.2. *Exponential (Log Phase)*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Once acclimated, each frond buds at its characteristic rate, producing rapid population expansion. (Yang, 2022) Because reproduction is independent of mating, growth can be very fast, with doubling times as short as 1 to 3 days depending on conditions. (Coughlan et al., 2022) This rapid growth allows duckweed to quickly cover the water surface. 


2.3.3. *Plateau (Stationary) Phase*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Exponential growth cannot continue indefinitely. As the mat thickens and density increases, growth slows due to density-dependent factors such as self-shading and waste accumulation. (Walsh et al., 2021)


<br> **2.4. Factors Affecting Growth**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Several environmental and physiological factors influence duckweed growth in controlled systems. Light intensity and photoperiod affect photosynthesis and biomass accumulation, while temperature influences metabolic rates and reproduction speed. (Islam et al., 2025) Nutrient availability, particularly nitrogen, phosphorus and micronutrients, directly impact frond production and protein content. (Ruvini Hiththatiyage et al., 2026) Water quality parameters such as pH and the presence of toxins or pollutants can also limit growth. (Jones et al., 2023) Additionally, overcrowding and self-shading in dense mats can slow reproduction, (Walsh et al., 2021) while the accumulation of microbial films on the fronds can further inhibit growth. (Zhang et al., 2010) 


<br> **2.5. Indicators of Poor Growth**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Poor duckweed growth can be identified through several observable signs. Healthy fronds float on the water surface, but stressed or unhealthy ones may produce turions, which sink, indicating reduced buoyancy or survival strategy under stress. (Ziegler et al., 2023) Discolouration, such as white or yellowed fronds, can signal nutrient deficiencies, disease or environmental stress. (Bunyoo et al., 2022)


# 3. Biofilm (Shannen) 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Biofilms originate from microorganisms naturally present in water, including bacteria, fungi, algae and protozoa, which can attach to any suitable surface in a moist environment. (Ali et al., 2023) These microorganisms secrete a self-produced matrix called extracellular polymeric substances (EPS), made of polysaccharides, proteins, DNA and water, which protects the community and enables its expansion. (Zhao et al., 2023) While environmental parameters can be precisely controlled in indoor cultivation systems, biofilm readily establishes and exhibits high resilience, presenting a significant challenge to maintaining healthy duckweed culture. This section examines the growth of biofilm and its negative interactions with duckweed.

<br> **3.1. Physical Characteristics**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Duckweed is a small, fast-growing aquatic plant that floats on the surface of freshwater and reproduces primarily through asexual budding, producing genetically identical plants that contribute to rapid colony formation. It is one of the smallest plants, typically 1-15 mm in length, with simple, flat, oval-shaped fronds. (Ziegler et al., 2023) The fronds are buoyant due to air-filled tissues, which help keep the plant afloat (Chen, 2024) and  form dense mats on the water surface. (Walsh et al., 2021) Duckweed naturally grows in still or slow-moving freshwater bodies and can tolerate a range of environmental conditions. (Thingujam et al., 2024) 

<br> **3.2. Stages of Biofilm Development**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Biofilm formation occurs in five main stages. It begins with the attachment stage, where free-floating bacteria loosely adhere to surfaces through weak forces like van der Waals interaction and electrostatic attraction. This is followed by irreversible adhesion as bacteria anchor and initiate production of the EPS. Next, in the microcolony formation stage, the attached bacteria proliferate and aggregate into small clusters. During the maturation stage, the biofilm develops into a complex three-dimensional structure with the microcolonies. Finally, in the dispersion stage, some bacteria detach to colonise new surfaces, allowing biofilms to spread and re-establish elsewhere. (Ugwu et al., 2025) 

<br> **3.3. Sources and Growth Drivers**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In duckweed cultivation, microorganisms are readily introduced through the water source, nutrient solutions or handling of the plants. (An et al., 2024) Biofilm formation is driven by the presence of available surfaces for attachment, sufficient moisture and nutrients that sustain microbial metabolism. (Ugwu et al., 2025) Environmental conditions common in cultivation, such as stagnant water, warm temperatures and high nutrient conditions, further accelerate biofilm development. (Li et al., 2023) 

<br> **3.4. Negative Impact of Biofilm Adherence on Duckweed Growth**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Although biofilms can be beneficial in some contexts such as stabilising ecosystems, recycling nutrients or supporting beneficial microbial communities (Musa et al., 2024), they are detrimental to duckweed cultivation in controlled systems. On duckweed fronds, biofilms adhere to the plant surface, physically obstructing frond reproduction (Zhang et al., 2010) and hindering nutrient uptake, leading to slower growth and lower biomass. Additionally, biofilms can harbour competing or pathogenic microbes, further compromising plant health (An et al., 2024) and potential for safe consumption. (Zięć et al., 2025) Although a dense duckweed population can partially limit biofilm accumulation (Beitle et al., 2025), this comes at the cost of reduced productivity and continued negative impacts on overall crop performance.


# 4. Value Proposition (Shannen) 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To address the problem of biofilm in duckweed cultivation, we identified stakeholders impacted and evaluated current management measures, recognising that existing methods are few, disruptive and labour-intensive. The proposed system aims to provide a non-destructive and automated biofilm management by monitoring fronds in real time and applying a novel removal method. 

<br> **4.1. Design Product**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The goal of this project is to develop a system that utilises a camera to monitor biofilm formation and adherence in real time, and automatically triggers a mechanical removal mechanism when biofilm is detected.

<br> **4.2. Stakeholder Analysis**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We were inspired by Dr Yuchen Long’s research on duckweed and visited his lab, where he shared that he encountered significant biofilm contamination while cultivating duckweed. He explained that biofilm can rapidly cover plant surface and system components, competing with duckweed for nutrients, oxygen and light, while also harbouring potentially harmful microorganisms, and is difficult to remove once established. Currently, the lab uses bleaching to control biofilm, which risks damaging the crop, highlighting the need for alternative solutions to support healthy duckweed growth. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In line with Singapore’s goal of strengthening local food production, the primary stakeholders of the project are indoor farming operations, which require efficient and reliable systems to maintain microgreen cultivation. (EDB Singapore, 2025) These users would benefit from improved biofilm management, resulting in higher productive and reduced reliance on labour-intensive or potentially damaging control methods. Farm technicians and workers are also key stakeholders as they are responsible for operating and maintaining the system. 
	
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Secondary stakeholders include researchers and R&D institutions who are interested in advancing duckweed cultivation and biofilm management strategies. In addition, consumers represent a broader stakeholder group, benefiting from safer and more sustainable food production enabled by improved cultivation practices.		

<br> **4.3. Current Biofilm Management Techniques**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Currently, no commercial or standardised systems provide real-time detection and removal of biofilm from duckweed fronds. While laboratory protocols exist for sterilisation of duckweed and hydroponic technologies can manage general biofilm, there is no integrated solution that combines continuous monitoring with duckweed-specific biofilm control.

4.3.1. *Lab Protocols for Biofilm Removal*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Laboratory protocols have been developed specifically for duckweed, focussing on surface sterilisation and gentle rinsing, where fronds are briefly soaked in dilute sodium hypochlorite (~1% bleach) followed by multiple rinses to remove surface microbes and loose biofilm. (Laurich, 2019) 

4.3.2. *Biofilm Management in Hydroponics Systems*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In broader hydroponic systems, biofilm is managed using physical and mechanical methods, such as scrubbing or flushing surfaces, ultrasonic or sound-based disruption and UV. (Mehmood et al., 2025) Chemical interventions are also commonly applied. (An et al., 2024) 

4.3.3. *Current Biofilm Detection Methods*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microscopical and imaging methods are among the most commonly used for biofilm detection, enabling direct visualisation of biofilm structure and thickness. In addition, biological approaches such as colony-forming unit assays, are also employed to estimate viable microbial populations by culturing biofilm cells on agar plates. Chemical techniques use staining assays and analysis of EPS or metabolic activity to quantify biofilm presence. (Achinas et al., 2020) Optical and spectroscopic methods further complement these techniques by quantifying biofilm growth through changes in light absorption, reflection or molecular composition. (Kulshrestha & Gupta, 2024) More recently, sensor-based and physical detection methods have emerged, including optical fibre sensors (Rakhimbekova et al., 2022) and capacitive sensors. (Zirk et al., 2022)

<br> **4.4. Gaps in Existing Approaches and Our Proposed Solution**

4.4.1. *Evaluation of Current Biofilm Management Methods*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Laboratory protocols for duckweed are not suitable for continuous or large-scale cultivation. These methods are labour-intensive and may disrupt normal duckweed growth if applied repeatedly, while also failing to prevent rapid re-establishment of biofilm due to the chemical resistance of the EPS matrix. (Hasan & Aggarwal, 2024) In hydroponic systems, existing mechanical methods could potentially be adapted to remove biofilm from duckweed surfaces without relying on harsh chemicals that pose safety concerns for human consumption. (An et al., 2024)

4.4.2. *Evaluation of Current Biofilm Detection Methods*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Laboratory methods, such as microscopy and imaging, provide detailed visualisation of biofilm structure but are destructive, labour-intensive and unsuitable for continuous monitoring. Similarly, biological approaches can quantify viable microbes but they are slow and do not capture non-culturable cells or the EPS matrix. Chemical techniques can detect and quantify biofilm more directly, yet they require sampling and cannot provide real-time feedback. (Achinas et al., 2020) In contrast, optical and sensor-based approaches show the most promise for monitoring biofilm on duckweed. Optical techniques allow non-invasive and rapid tracking of biofilm growth and composition (Kulshrestha & Gupta, 2024), while emerging sensors can provide real-time and non-destructive detection. (Rakhimbekova et al., 2022) 

4.4.3. *Limitations Addressed*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We propose an integrated, real-time system specifically designed for duckweed cultivation. The approach uses camera-based imaging to continuously monitor biofilm formation on duckweed fronds. Image analysis algorithms quantify biofilm growth and trigger a signal when biofilm exceeds set thresholds. This signal then activates a mechanical removal mechanism to eliminate biofilm from the plant surface. By combining automated detection with targeted mechanical removal, the system provides non-destructive, continuous, real-time biofilm management while reducing labour requirements. 


<br> **1.4. Interaction between Cyanobacteria and Duckweed**

![Figure A](duckweed.png)
<div style="text-align: center;"> Figure A: Duckweed Cultivation with Cyanobacteria and Algae </div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cyanobacteria can establish populations in the water during duckweed cultivation. Even at concentrations as low as 0.075µg/mL, cyanobacteria significantly reduce duckweed growth and chlorophyll content. (Saqrane et al., 2007) Duckweed is a free floating plant and cyanobacteria at these concentrations often remain at the water surface alongside the plants. (Delgopiatof et al., 2024) Thus, it is important to maintain low cyanobacteria levels in cultivation systems to optimize duckweed growth and protein yield.

# 2. Design Product
**2.1. Value Proposition** (Jingten) 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Our goal of the project and value proposition is: to develop a low-cost real-time optical sensor with an integrated filter to prevent cyanobacteria growth in indoor duckweed farms. 

<br> **2.2. Stakeholder Analysis** (Jingten)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As indoor farms struggle to remain viable due to the high cost of set up and extensive energy demand, we aim to create a low cost sensor for SME indoor farms that allows them to integrate smart agriculture to increase yield and reduce loss. 
	
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We were inspired by Dr. Yuchen Long’s research on duckweed, and through the conversation we learnt the negative impact of phytoplankton contamination in duckweed tanks may take over the space and greatly compete with duckweed for available nutrients and space. However, as both duckweed and cyanobacteria use the same nutrients for growth, without the use of algaecide, it is difficult to eliminate cyanobacteria. He mentioned that it is crucial to promote duckweed growth at an early stage as it could suppress cyanobacteria proliferation by taking up the nutrient and light required for photosynthesis and cyanobacteria. This could be applied in indoor duckweed farms, as cyanobacteria growth is commonly found in hydroponics systems.


<br> **2.3. Design Requirements** (Shannen) 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Our target users are small and medium enterprises (SMEs) indoor farms in Singapore. We aim to provide a solution that is affordable, easy to maintain and simple to operate, while ensuring reliable detection performance. To meet these goals, the design of our optical cyanobacteria sensor is guided by the following considerations: 

2.3.1. *Practical Considerations*


| |  |
| :--- | :--- |
|  **Affordability** | The unit price should remain below SGD $1,000 to ensure accessibility for SMEs to encourage adoption. The lowest price on the market is USD [1,995<sup>1</sup>](#footnote-1). |
|  **Portability** | The sensor must be compact and lightweight to support relocation within multi-tank facilities. Transfers should be quick and non-disruptive to farming operations.  |
| **Ease of use** | The sensor should be simple to operate for users with minimal technical training. Sensor readings and real-time cyanobacteria concentrations must be easily accessible and clearly interpreted. This includes an intuitive user interface, clear display of results and guided workflow. Furthermore, users can collect readings without disturbing the duckweed or water system.  |

2.3.2. *Technical Considerations*

| |  |
| :--- | :--- |
|  **Detection Limits** | The sensor must detect cyanobacteria concentrations low enough to prevent harmful effects on duckweed. Growth and chlorophyll content of duckweed decrease significantly at 0.075 μg/mL =7.5106 cells/mL. (Saqrane et al., 2007) Therefore, the system must trigger alerts at or below this threshold to ensure early intervention.  |
|  **Ease of Maintenance** | The device should remain functional with minimal servicing effort and without requiring users to handle water or internal components. Maintenance procedures must be simple, safe and infrequent. <br> &nbsp;&nbsp;- Accessible components: no need for users to submerge their hands or remove the sensor fully from the system.<br> &nbsp;&nbsp;- Long operational lifespan: battery designed to last 3 months without replacement or charging. <br> &nbsp;&nbsp;- Regular sampling: assuming cyanobacteria can double every 1.5-2 hours under favourable conditions (Wend et al., 2022), the measurements will be taken at least once every 3 hours to capture exponential growth phases. <br> &nbsp;&nbsp;- Minimal calibration: system calibration should remain stable over time with clear prompts when checks are needed.   |
| **Filter Specification** |The filter should effectively separate duckweed from the water to be filtered, and the cyanobacteria should be removed from the filtered water.   |

# 3. Detail Design 
Our proposed design is made out of three components.


|Component | Description |
| :--- | :--- |
|  **Sensor** | Measures the absorbance of water in duckweed tanks at 620nm correlated to the phycocyanin pigment in cyanobacteria. |
|  **Calibration and Processing** | Translates the absorbance readings measured by the sensor into cyanobacteria count.  |
| **Filter** | Removes the cyanobacteria from the duckweed tank.  |

<br> **3.1 Sensor** 

3.1.1. *State-of-the-Art Review* (Jingten)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Monitoring cyanobacteria is critical in water quality management and agriculture. However, most existing methods are designed for large scale environments like lakes, reservoirs and drinking water systems, and their application to compact, controlled setups like indoor duckweed farms remains limited. Current methods that are commonly used suffer from the trade-off between convenience and accuracy. 
	
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Methods such as ELISA kits (immunoassay-based) and Liquid Chromatography-Mass Spectrometry (LC-MS, chemical quantification of cyanotoxin) detect cyanotoxins with high specificity, but it requires lab processing, trained personnel, expensive and non-portable, thus not suitable for real-time or in-situ monitoring.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To provide timely alert of cyanobacteria growth for indoor duckweed farms, real-time sensing is vital. The current available technology could be summarized as satellite imaging, imaging with machine learning, and optical sensors. Satellite imaging that tracks surface-level bloom is commonly used for large water bodies, which lacks resolution for small-scale indoor systems. (NC State, 2021) Alternatively, machine learning may be applied along with imaging. While it is promising, they often depend on large datasets and computational resources, making it costly and highly dependent on the available data for training. Therefore in our project, we choose to focus on optical sensors, which are the most common form of sensor available on the market that provides real-time sensing. 
	
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Currently most optical sensors used for field research are fluorescence-based. While it is a promising solution for in-situ monitoring, its accuracy and reading is highly affected by environmental factors such as turbidity, temperature, or pH, which leads to unreliable estimation of biomass. Additionally, the complex calibration process also acts as a barrier to easy adoption by users to whom cyanobacteria monitoring may be a component to a complex system like duckweed farm.
	
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To simplify the complex system and lower the cost of production, our project focuses on absorbance-based sensors. While it has lower accuracy compared to the fluorescence-based sensor, it is a necessary trade-off for it to address the limitation of cost and complexity in existing sensor systems.


3.1.2. *Development of the Optical Sensor* (Isaac)

We have developed 4 concepts and will assess which concept best addresses the design requirements.

Submerged Long Term (LT) Line Power

Submerged Battery Inductive

Separated External Line Power

Separated External Battery

| | Line Power | Battery |
| :--- | :--- | --- |
|  **Submerged Unified** | Submerged Long Term (LT) Line Power | Submerged Battery (inductive) |
|  **Separated External** | Separated External Line Power | Separated External Battery |

| | Submerged Long Term [LP<sup>2</sup>](#footnote-2) | Submerged Battery Inductive | Separated External LP | Separated External Battery |
| :--- | :--- | --- | --- | --- |
|  **Affordability** | ++ | + | ++ | ++ |
|  **Ease of Set Up** | + | +++ | ++ | ++ |
|  **Operational Endurance** | +++ | ++ | +++ | ++ |
|  **Ease of maintenance** | + | ++ | ++ | ++ |
|  **Accuracy (all with the same internals)** | ++ | ++ | ++ | ++ |
|  **Ease of measurement and viewing of results** | + (no 7 segment display, direct connection to computer) | + (no 7 segment display, direct connection to computer)| ++ (have 7 segment / LCD display) | ++ (have 7 segment / LCD display) |
|  **Portability** |+ | +++ | ++ | ++ |
|  **Total Score** | 11 | 14 | 15 | 16 |


**Analysis of Concept Variations (Isaac)**

![Figure H](submerged_line.png)
<div style="text-align: center;"> Figure B: Submerged Unified Long Term (LT) Line Power </div>

This design is simple and straightforward with direct line power to a submerged sensor. It has operational endurance as it is place-and-forget. However, it is not portable and cannot be moved from tank to tank easily to take different measurements. 

![Figure G](submerged_inductive.png)
<div style="text-align: center;"> Figure C: Submerged Unified Battery Inductive design </div>

A variation of the first design is a submerged sensor that is inductively powered. This has good operational endurance as the sensor can be inductively powered and is less logistically complex, without power supply entering the water from the mains. However, it will be less affordable due to the inductive charger and better waterproofing is required as it is submerged.  

![Figure F](separated_line_power.png)
<div style="text-align: center;"> Figure D: Separated external line power </div>

To improve on this design, the sensor can be mounted on the side of the tank and the sampling mechanism is a tube that is suspended in the water. This requires less waterproofing for the sensor, however, it is externally powered. It will be affordable. 

![Figure I](separated_external.png)
<div style="text-align: center;"> Figure E: Separated External battery </div>

The last and final design we decided on is the separated external sensor with a inbuilt battery. This gives the best balance of portability (ease of transferring the sensor to another tank), and ease of maintenance as the battery removal is convenient on the outside of the tank. 

**Detailed Design of Sensor Module**

![Figure E](sensor.png)
<div style="text-align: center;"> Figure F: Integrated cyanobacteria spectral sensor with display and sampling mechanism </div>

The sensor comprises of 9 key components, divided into 4 systems. Sampling, Measurement and Computation, Power Management and Display.

**Sampling System**

Cuvette
Small peristaltic fluidic pump
Full Spectrum LED
620 nm Filter
Full Spectrum CMOS sensor

**Measurement and Computation**

Raspberry Pi Zero 2 W

**Power Management**

LiPo Battery 8000mAh
ESP 32 Microcontroller

**Display**

7 Segment LED Screen

**Operational Cycle**
1. Water is deposited using the small fluidic pump from the tank into the cuvette
2. Full Spectrum LED iluminates sample, light passes through cuvette and 620nm bandpass filter to CMOS sensor
3. Intensity of light is logged
4. Raspberry pi Zero 2 W calculates and outputs the cyanobacteria concentration.
5. Readings are displayed on 7 segment LED screen.

3.1.3. *Points of Consideration* (Jingten) 

![Figure K](cyano_pipe.png) 
<div style="text-align: center;"> Figure G: Cyanobacteria in Water Column Layers (Erratt et al., 2022) </div>

1. Location of the sensor (depth)
2. Numbers of sampling sites

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As the sensor plays the pivotal role to trigger any actions, it is important that the value detected is representative of the whole duckweed tank. While most cyanobacteria bloom occurs on the surface, cyanobacteria are not limited to the epilimnion layer of the water body. (Erratt et al., 2022)  Toxin-producing cyanobacteria could be present throughout the water column, and the density at which they occur could vary. (de Boutray et al., 2011) Therefore we have to consider whether to homogenize the water right before sampling for a generalized sample, or to further consider the location in which the sensor is placed and the number of sampling sites that would produce a reliable, unbiased value. 


<br> **3.2. Calibration Curve Relating Absorbance and Concentration of Cyanobacteria** (Shannen) 

![Figure B](calibration_curve.png)
<div style="text-align: center;"> Figure H: Flowchart of Calibration Curve Creation </div>


3.2.1. *Cell Culture*

1. Prepare 50 mL of growth medium in a flask using the same nutrient composition for duckweed growth.
2. Use a portion of the duckweed culture solution as the inoculum to initiate the cyanobacteria culture.
3. Cover the culture using parafilm to prevent contamination.
4. Allow the culture to grow in the same temperature and light conditions used for duckweed.
5. Take regular measurements to determine when the culture concentration reaches 1x10<sup>8</sup> cells/mL, using the cell counting protocol below.
6. Repeat steps 1-5 to prepare additional cyanobacteria cultures and grow for the determined incubation periods. 


3.2.2. *Cell Count*

1. Centrifuge 10 mL of cell suspension for 10 mins at 3000 x g. Discard the supernatant. (Rudi et al., 1998)
2. Resuspend the pellet in 8 mL of deionised water.
3. Load 6 µL of solution into the sample injection point on the hemacytometer (Figure 1).
4. Place the counting chamber on the stage of the microscope and focus on the cells.
5. Count the cells in the squares labelled A to E (Figure 1).
6. Calculate cell concentration using:


	![Figure L](3.2_cell_count.png)


7. Keep remaining suspension as stock solution for calibration curve dilutions. 

3.2.3. *Absorbance Measurements*

1. Set the wavelength as 665 nm on the UV-Vis spectrophotometer.
2. Pipette 1 mL of deionised water into the reference and sampling cuvette.
3. Wipe the cuvette surface and place the reference and sampling cuvette in the spectrophotometer.
4. Blank the background medium absorbance.
5. Pipette 1 mL of cell suspension into the sampling cuvette and measure absorbance. 


3.2.4. *Standard Calibration Curve*

1. Mix the cell suspension and prepare dilution series in deionised water.
2. Mix 2 mL of the given cell culture with 2 mL of deionised water (1:2) in a centrifuge tube (10 mL capacity).
3. Mix 2 mL of the resultant diluted cell suspension with 2 mL of deionised water in another tube (1:4).
4. Repeat the process until you have produced 10 dilutions. After each dilution, mix well and use a new pipette tip for the next dilution.
5. Measure the optical density of the stock and diluted cell suspensions using UV-Vis spectrophotometer.
6. Calculate absorbance using the Beer-Lambert Law: A: absorbance, દ: molar absorptivity, l=1 cm: path length of the cuvette and c: cell concentration

	![Figure M](beer.png)

7. Plot absorbance against cell concentration to obtain a calibration curve. 



3.2.5. *Reading Processing* (Jingten)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The absorbance at specific wavelengths associated with cyanobacterial pigments will be processed to estimate cyanobacterial density through an analytical workflow using the calibration curve obtained. First, the raw absorbance data is corrected for background interference by subtracting non-specific signals from blank readings, caused by turbidity or dissolved organic matter from duckweed growth to ensure specific absorbance. The corrected value is applied to the calibration curve obtained using known concentration of cyanobacteria, which defines the mathematical relationship between absorbance and bacteria density through the Beer-Lambert Law. The sensor outputs a real-time estimate of cyanobacterial density, which will be displayed at the side of the tank with an optional alert system when threshold density is exceeded. This enables farmers to monitor cyanobacteria dynamics continuously and intervene before the bacteria contamination affects duckweed health. 


<br> **3.3. Removal and Management of Detected Cyanobacteria** (Jingten)

The filter is divided into two core functions:
- Cyanobacteria cell removal: physically separates cyanobacteria from the main duckweed tank 
- Cyanotoxin neutralization: neutralizes dissolved cyanotoxins released by cyanobacteria in the water

3.3.1. *Filter*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To separate cyanobacteria from the main duckweed tank, a 74 μm pore size mesh is used to prevent duckweed from leaving the tank, whilst allowing the cyanobacteria and suspension to be transferred into the 2nd tank. The pore size is smaller than the smallest duckweed species, Wolffia, at 0.1mm or 100 μm, which makes it ideal for separating the cyanobacteria from duckweed. (Acosta et al., 2021)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To remove cyanobacteria, microscreen filters (10 μm mesh) can be used to trap suspended cyanobacteria cells. These filters are widely adopted in aquaculture and water treatment for their efficiency and scalability, and have been shown to effectively remove majority of the phytoplankton in the water. (Czyżewska & Piontek, 2019)

In addition to mechanical filtration, flocculants such as chitosan and polyaluminium chloride (PAC) are used to aggregate cyanobacteria into larger masses called flocs that settle or filter more easily. (Noyma et al., 2016) While chitosan is commonly preferred for its plant-safe applications due to low toxicity, it is shown to damage Microcystis aeruginosa through lysing the cells, causing the cyanotoxins to be released into the water. (Serrà et al., 2021) With this in mind, the chemical coagulation of cyanobacteria through flocculants will be completed in a separate tank to prevent the direct contact between the duckweed and toxins, and the potential uptake of the toxins by duckweed plant.

![Figure J](filter.png)
<div style="text-align: center;"> Figure I: 2 tank filter mechanism to remove cyanotoxins and recover nutrients (nitrogen and phosphorous) (Isaac) </div>

3.3.2. *Management of Cyanobacteria*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After cell removal, dissolved toxins may remain in the water. Given the high cyanobacteria growth rate, it is highly likely the water is rich in essential nutrients for plant growth such as nitrogen and phosphorus, it should not be simply discarded to fully utilize the nutrients and prevent fertilizer runoff that causes downstream eutrophication. We aim to remove the cyanotoxins present in the water following the removal of cyanobacteria cells, and reuse the water in the main duckweed tank. 
One of the most widely used methods for cyanotoxin removal is activated carbon adsorption. This relies on the porous structure of activated carbon to physically adsorb dissolved cyanotoxins from the water. However, its performance could be hindered by factors such as contact ime, carbon type, water quality, and the process can be costly due to the need for regeneration and reactivation of the carbon. (Abbas et al., 2020)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Another novel alternative to degrade cyanobacteria is potassium permanganate, which is a strong oxidizing agent that has been shown to effectively oxidize cyanotoxins such as microcystins and anatoxins into non-toxic form by alternating the molecular structure. (Li et al., 2021) Cyanotoxins is shown to be effectively neutralized by adding the optimal dosage of the potassium permanganate, and it is shown to cause less damage to the cellular membrane of cyanobacteria, leading to lower extracellular cyanotoxin levels. Considering the simplicity and cost of the method, we intend to explore the integration of potassium permanganate dosing in the system.


# 4. Validation of Design (Jingten)

**4.1. Cyanobacteria and Duckweed Growth** 

1. Using the appropriate environmental conditions and growth medium, allow duckweed and cyanobacteria to grow in a tank.
2. Take regular measurements to determine when the cyanobacteria level reaches 1x10<sup>8</sup> cells/mL, using the cell counting protocol above. 


<br> **4.2. Measurements Using UV Spectrometer and Our Sensor**

1. Take frequent measurements using the UV spectrometer.
2. Record the corresponding sensor reading.
3. Repeat measurements at different locations as cyanobacteria populations can be non-homogeneous.  


<br> **4.3. Determination of the Sensor’s Accuracy**

To confirm whether the biosensor accurately tracks cyanobacteria pigment concentrations and population density. 
1. Plot sensor-derived cell concentrations with hemocytometer counts to validate interpretation of optical signals. /n

	![Figure N](sensor_cell.png)

2. Calculate the accuracy using 

	![Figure O](percent_error.png)

3. Refine calibration if needed, using regression analysis to improve the mapping between optical signal and actual cell concentrations.


<br> **4.4. Determination of the Sensor’s Sensitivity**

Validate that the biosensor can reliably detect concentrations at or below 0.075 μg/mL, ensuring it meets the early warning design specification. 
1. Plot sensor readings against the UV spectrometer absorbance values.

![Figure P](sensor_ab.png)
2. Perform regression analysis to determine correlation and establish a calibration equation.
3. Calculate the limit of detection (LOD) and limit of quantification (LOQ) using (Tabarin et al., n.d.):
- SD of Blank is the standard deviation of 5 blank measurements of the growth medium using the sensor. 

![Figure Q](lod.png)


<br> **4.5. Impact of Filter on The Duckweed Tank System**

1. With an undisturbed duckweed tank as control, measure the impact of integrating the filter into the system with varied filter frequency (every 12 hours, 24 hours, 36 hours, 48 hours). As agitated water surface is shown to be a stressor in duckweed growth (Ziegler et al., 2023), it is vital to establish that the filtration method to remove cyanobacteria from the tank does not significantly impact the duckweed growth.
2. Additional mitigation methods for cyanobacteria in the water tank should also be studied for their effects on the duckweed growth, which is quantified by the following criteria: duckweed growth rate (doubling time), dry mass, total mass, and dormant turion formation in duckweed tank.
3. Using the appropriate environmental conditions and growth medium, allow duckweed and cyanobacteria to grow in a tank.


# 5. Project Plan (Jingten)
**5.1. Gantt Chart**

![Figure C](gantt_chart.png)
<div style="text-align: center;"> Figure J: Gantt Chart of Semester 2 </div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Gantt Chart outlines the timeline for the prototyping and testing phase of the project to be carried out in the next semester over 10 weeks. To optimize for efficiency, the biosensor hardware development is carried out concurrently with biological preparations (sample cultivation). While the testing span throughout the whole chart due to the duckweed tank setup, testing the biosensor hinges on the design and assembly of the biosensor. Therefore, activities with high priority are carried out at the start of the prototyping phase.

<br> **5.2. Project Risk Assessment**

Several risks have been identified that could impact the timeline of the project:

|Risks | Consequence | Mitigation |
| :--- | :--- | :---: |
| Contamination in cyanobacteria culture | Unable to create calibration curve | Maintain backup culture past the phase |
|   Duckweed death | Unable to conduct field testing | Maintain backup culture past the phase |
|Cyanobacteria density not dense enough for sensing | Sensor unable to provide reliable readings for analysis | Centrifuge to concentrate the cyanobacteria culture and more growth medium |
| Prototype components not delivered in time | Unable to build prototype | Explore alternative local suppliers (even at a higher cost) and push back the testing phase | 
| Components failure/destroyed during assembly | Biosensor unable to function. Getting the components again may lead to delay in timeline | Buy spare supplies and explore alternative materials |

<br> **5.3. Laboratory Use**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;All biological work (cyanobacteria cultivation, calibration curve development, duckweed culture) will be conducted in a Biosafety Level 1 (BSL-1) lab with facilities such as spectrophotometers, microscope, and centrifuge. As this serves as the basis for the calibration curve and further testing and validation, culturing duckweed and cyanobacteria will be the first step in the prototyping phase, and for the first four weeks, it will be monitored every two days to ensure healthy growth. 
Duckweed tanks will also be set up in the field testing phase.

# References

Abbas, T., Kajjumba, G. W., Ejjada, M., Masrura, S. U., Marti, E. J., Khan, E., & Jones-Lepp, T. L. (2020). Recent Advancements in the Removal of Cyanotoxins from Water Using Conventional and Modified Adsorbents—A Contemporary Review. Water, 12(10), 2756. https://doi.org/10.3390/w12102756

Acosta, K., Appenroth, K. J., Borisjuk, L., Edelman, M., Heinig, U., Jansen, M. A. K., Oyama, T., Pasaribu, B., Schubert, I., Sorrels, S., Sree, K. S., Xu, S., Michael, T. P., & Lam, E. (2021). Return of the Lemnaceae: duckweed as a model plant system in the genomics and postgenomics era. The Plant cell, 33(10), 3207–3234. https://doi.org/10.1093/plcell/koab189

An, C., Ye Htut Zwe, Mei, M., Shang, G., Ling, Y., Poh, B. L., Zhou, W., & Li, D. (2024). Sanitization of hydroponic farming facilities in Singapore: what, why, and how. Applied and Environmental Microbiology. https://doi.org/10.1128/aem.00672-24

Anthem, P. (2025, July 7). Food security – what it means and why it matters. World Food Programme. https://www.wfp.org/stories/food-security-what-it-means-and-why-it-matters

Appenroth, Klaus-J., Sree, K. S., Böhm, V., Hammann, S., Vetter, W., Leiterer, M., & Jahreis, G. (2017). Nutritional value of duckweeds (Lemnaceae) as human food. Food Chemistry, 217, 266–273. https://doi.org/10.1016/j.foodchem.2016.08.116




# Appendix

Definitions of Key Terms 
1. Undernourished: The prevalence of undernourishment is defined as the proportion of the population in each country who, on a regular basis, consume food in amounts that are insufficient to provide the energy required for a normal, active and healthy life. (FAO et al., 2025)
2. Malnutrition: Malnutrition is a serious condition that occurs when a person does not receive the right amount of nutrients. (Tan, 2019)


|Product Description | Product Link | Price [(SGD)<sup>3</sup>](#footnote-3) |
| :--- | :--- | --- |
|  **Full Spectrum CMOS Sensor (with no bayer filter) OV7251 MIPI Global Shutter CMOS LI-OV7251M-FF-80 Monochrome 640 x 480 MIPI** | https://www.digikey.sg/en/products/detail/leopard-imaging-inc/LI-OV7251M-FF-80/21324197 | 83.59 SGD|
|  **620 nm narrow bandpass filter (10nm bandwidth)** | https://www.edmundoptics.com.sg/p/everix-ultra-thin-narrow-bandpass-filter-620nm-125mm-dia-10nm-fwhm/52295/  | 104.55 SGD |
| **Raspberry Pi Zero 2 W** | https://my.cytron.io/p-raspberry-pi-zero-2-w-with-32gb-microsd?src=raspberrypi | 44.25 SGD |
| **ESP 32 Board** | https://shopee.sg/ESP-32-WIFI-Bluetooth-Development-Board-ESP32-ESP-32S-i.189216177.3653344782 | 5.29 SGD |
| **LiPo Battery (8000mAh)** | https://www.ebay.com.au/itm/187166362807 | 24.55 SGD |
| **Microfluidic Pump (4mm diameter)** | https://www.foreshinefluid.com/en-sg/products/0-270ml-min-constant-flow-miniature-peristaltic-dosing-pump-12v-dc-water-pump | 13 SGD |
| **Full Spectrum LED (10 pcs)** | https://www.digikey.sg/en/products/detail/dialight/5218743F/26266920 | 4.42 SGD |
| **7 segment LED Screen TM1637 Display Module** | https://shopee.sg/7-Segment-Display-4-Digit-LED-Module-TM1637-i.1418435781.29674184442 | 3.59 SGD |
| **4.5 ML Disposable Plastic Cuvette (8 pcs)** | https://shopee.sg/4.5ML-Disposable-Plastic-Cuvette-i.361504276.27011199278 | 4.91 SGD |
| | Total Price | 288.15 SGD |

**Calculations**

![Figure D](Hemacytometer.png)

<div style="text-align: center;"> Figure 1: Hemacytometer Counting Grid </div>

![Figure R](hema_eqn.png)





<span id="footnote-1"></span>1. <https://sensorpros.com/products/in-situ-aqua-troll-aqua-troll-chlorophyll-a-sensor-0038900?srsltid=AfmBOorIPGMrujqGgASiri6cVbLl3tHx-IxRXKehJ6gCBcPUa5xE43x_&variant=28530561843234>

<span id="footnote-2"></span>2. Long Term Line Power

<span id="footnote-3"></span>3. Conversion Rate based on 28 October 2025, 1 USD = 1.30 SGD, 1 SGD = 3.25 MYR, 1 GBP = 1.73 SGD
