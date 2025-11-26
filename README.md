# From Research to The Market
                                                        
Innovation is always fuelled by research. One of the goals of research is to commercialise the innovation so that the benefits are reaped by the masses and gives rise to scalability. Hence, this is a synthesis of knowledge contained in some of the innovative scientific papers that help solving manufacturing problems with data and AI . The notion of a new technolgy that can disrupt a manufacturing process is also delved upon.

## A] Predictive Maintenance:  
### 1. The What, Why and How    
Predictive maintenance of assets is a technique where in the working conditions of the asset on the production floor are constantly monitored in real time. The conditions such as the electrical inputs to the motor, the current and the voltage , the temperature or pressure readings , the vibration of the rotating parts, etc  are done with the help of sensors. The new age assets may have the sensors in built and for the older ones may need retrofitting. Hence the system needs a synergy of data capture through sensors, data storage and data analysis. 
Once the real time data is in place, it is checked for its quality and is further preprocessed i.e aggregated, new features extracted etc
Next, a simple simple condition based monitoring(Threshold based) of assets is implemented(This is the most low hanging fruit). We then make the process more smarter taking it to the next level i.e  with the help of machine learning and deep learning models , the prediction of the working state of the assets is done. The models can predict the remaining useful life of the asset with the required accuracy, helping the maintenance managers to plan for the downtime and to have the least number of downtimes that have the minimal impact on the production schedules and quality of the finished product. 

<a href="https://link.springer.com/article/10.1007/s40436-022-00433-x">Application of sensor data based predictive maintenance and artificial neural networks to enable Industry 4.0</a>





### 2. Further research    
a) How do you decide on which assets in your production line will benefit with Predictive Maintenance?  

Traditionally FMEA and FMECA help in identifying which asset in the production system is 'Critical', in the sense, if the asset fails the production halts, has high costs for repair and replacement , leads to quality issues , wastage and loss of revenue. The analysis leads to a Risk Priority Number(RPN). The higher the number more critical is the asset and smart asset maintenance is inevitable. 
Reactive Asset maintenance should be a strict no and other proactive techniques starting with Condition based Maintenance , and further leading to predictive maintenance needs to be tried and tested.

Deciding on the right asset maintenance technique needs to be driven by a framework. The framework is guided by the matching of the ambition level and the data readiness. 

<a href="https://www.researchgate.net/publication/368320424_Decision_Framework_for_Predictive_Maintenance_Method_Selection">Decision Framework for Predictive Maintenance Method Selection</a>

b) What are the benefits of a predictive maintenance platform? 

Should a company invest in a predictive maintenamce platform versus implementimng predictive maintenance of the asset which is the biggest bottle neck ? The following paper susggests that the value delivered through such a platform is more compounded as the platform can help in addressing multiple bottle necks on the plant floor . Selection of sensor type and placement is supported by FMECA or FMESA as presented in the standard ISO 17359:2018. If the costs justify, a predictive maintenance platform improves the value chain performance and provides contextual asset data. 

<a href="https://link.springer.com/article/10.1007/s40436-022-00433-x#Fig3">Application of sensor data based predictive maintenance and artificial neural networks to enable Industry 4.0</a>
   
c) What are the challenges with PdM ? 

Although predictive maintenance is the most efficient way of managing the working of an asset, it has a few limitations. The following paper delves further on the topic by reaching out to the industry and getting the pulse from the maintenance professionals . Its worth exploring further on if Generative AI can help in 'lack of capacity and skilled workers' by helping in SOP training, fault diagnosis etc .

<a href="https://link.springer.com/article/10.1007/s41471-024-00204-3?">Unlocking the Potential of Predictive Maintenance for Intelligent Manufacturing: a Case Study On Potentials, Barriers, and Critical Success Factors</a> 

## B] Sustainable Manufacturing:  
### Sustainability in manufacturing as a 'default' mode. 

a)Can we easily acquire the necessary data from the existing IT , OT systems for understanding the  existing level of sustainability and provide the required visibility ?  
b)How can we then automate and optimize the process further?  

Data related to product sustainability - regarding material, design, manufacturing processes, distribution , usage etc lies in in different systems. There is a need to have a unified view of the data with contextuality. Technolgy such as digital twin plays an important role. The data unification can be virtual as in the case of <a href="https://www.iiot.university/blog/what-is-uns%3F"> Unified Name Space </a> 
  
<a href="https://www.mdpi.com/2071-1050/17/16/7316">A Review of Digital Twin Integration in Circular Manufacturing for Sustainable Industry Transition</a> Enabling sustainability in manufacturing with digital twin frameworks that deliver incremental value.

<a href="https://link.springer.com/article/10.1007/s00170-022-09295-w"> A generic asset model for implementing product digital twins in smart remanufacturing </a> How can product digital twin  enable smarter remanufacturing . This paper provides a guideline of  building digital twin to mitigate some of the challenges.      

<a href="https://link.springer.com/article/10.1007/s00163-025-00458-w"> Carbon Reduction Engineering Framework </a> Sustainability needs to  be applied at every stage of manufacturing. Carbon Reduction Engineering Framework delves on mitigating against focusing only on the isolation lifecyle cases, neglecting the interactions across multiple lifecylce stages such as material sourcing, product use and recycling.It starts with product digitisation, breaking it down to component inventory and creating a baseline carbon footprint. The components with the highest carbon foorprint have the maximum scope for achieving higher carbon reductions using alternative sustainable material . This is followed by feasability study for the design and then the final step of definitive redesign modification. 

<a href="https://www.researchgate.net/publication/396407930_Sustainable_mechanical_design_and_manufacturing_of_pressure_relief_valves"> Valves- a suitable candidate for sustainable redesign and manufacturing </a> 
Valve manufacturimng is quite a carbon intensive process,  considering the material used and the manufacturing process. The traditional design consists of many parts that are assembled.  Also , industrial valves are prone for fugitive emissions - especially with most emissions coming from valve stems and fittings (joints). Redesigning valves for sustainability requires a comprehensive approach that considers the entire lifecycle of the valve, from raw material sourcing to end-of-life disposal. Sustainable redesign of pressure relief valves considers eco raw material such as polymers that have chemical and heat resistance , resulting  in fewer valve parts, easier assembly, less weight, and lower cost. 

LCA based FMEA for calculating the sustainability risks.<a href="https://www.sciencedirect.com/science/article/pii/S2352550924001283"> Sustainability risk assessment in manufacturing: A Life Cycle Assessment-based Failure Mode and Effects Analysis approach</a>  

How do we begin with redesigning a product for sustainability ? <a href="https://link.springer.com/article/10.1007/s00163-025-00458-w"> Proposing a carbon reduction engineering framework for product design: a multi-scenario perspective </a> 

### About: 
I am Vidya. I am engineer who started her career in software engineering. I have worked on design, development and maintenance of financial applications and ERP software. The most exciting career role was my work as a product owner, where in I mapped the business requirements to the software product features and lead my team in building, testing and productionising those features. 
I have subsequently moved to data domain, and mastered data analytics , machine learning and deep learning through various projects and work experience . Post my MSc in Digital Transformation and Smart Industries at National Univerisity of Singapore (2024), I am passionately working on Industrial AI Research, with the sole aim of leveraging the industrial data to solve the production problems. The goal is advance every factory to a smart and sustainable one. Keen to collaborate with companies on Industrial DataOps and AI.

### Contact: 
vidya.industrialairesearch@gmail.com
#### LinkedIn:
https://www.linkedin.com/in/vidya-m-shankar/


