# Group 6 - AI in Agriculture 
 

Author List:   
[Augie Cooper](https://github.com/sacooper01/AugieCooper/blob/main/README.md)  
[Ethan Snyder](https://github.com/ethansnyder4/EthanSnyder)  
Malachi Imoh  -- Link to page  
Rhys Nordstrom  -- Link to page  

Nice visuals to illustrate your main concepts and why this project is important for businesses.  
![image](https://github.com/user-attachments/assets/067bf623-5c8f-4d1b-ae20-bc7bdf9d3b64)  
[https://www.youtube.com/watch?v=OWM2iF7S8Jw](https://youtu.be/OWM2iF7S8Jw?si=J8L2TB4WRplsWdyn)  

**Precision agriculture (PA)** is a management strategy that gathers, processes and analyzes temporal, spatial and individual plant and animal data and combines it with other information to support management decisions according to estimated variability for improved resource use efficiency, productivity, quality, profitability and sustainability of agricultural production.


**Project Scope:**
Monitoring livestock health is a critical component of modern dairy and meat production. Traditional methods—such as manual observation—are time-consuming, labor-intensive, and often inconsistent. As a result, issues may go unnoticed until they become serious. With the rise of computer vision and IoT technology, it is now possible to monitor cattle health continuously and in real-time, enabling earlier interventions and improving animal welfare and farm productivity.

Our project focuses on a narrow yet impactful task within this larger ecosystem: developing a neural network classifier that predicts the health status of cattle using structured data derived from computer vision and sensor-based monitoring systems.

**Project Details:**  
In the agriculture industry, emerging technologies—such as those developed by companies like Precision Livestock Technologies—are capable of autonomously identifying cows and tracking key physiological and behavioral metrics, including:  
 - Weight
 - Body temperature
 - Sociability and interaction patterns
 - Rumination time
 - Movement and activity levels  

These systems generate structured datasets that serve as the input for our model.  
Our contribution is the creation of a binary classification model that places each cow into one of two health zones:
 - Healthy
 - Needs Attention
 
We accomplish this by building and training a neural network classifier using historical labeled data. The model takes multiple numerical and categorical features (derived from computer vision and IoT sources) and outputs a predicted health class. The classifier is designed to support early identification of health issues, helping farmers prioritize which animals require intervention. 

To extend the usefulness of our model, we developed a web application using Claude AI. This platform provides:
 - Real-time updates on individual cattle health
 - Visual dashboards displaying metrics and model outputs

**Future developments and concerns.** 

Future considerations include improving model accuracy through larger datasets, expanding the classification labels beyond binary health zones, incorporating time-series analysis, potential integration with existing IoT ecosystems for seamless data flow, and  health alerts and notifications when an animal shifts from "Healthy" to "Needs Attention"

**Considerations**
 - Privacy
 - Accountability
 - Stress on animals (over intervention)
 - Environmental


**References:**
 - https://www.researchgate.net/publication/388666536_Sensor_and_Computer_Vision_Based_Cattle_Health_Monitoring_and_Management
 - https://dac.digital/case-studies/how-our-ai-driven-algorithms-enabled-the-detection-of-early-signs-of-cows-diseases/#:~:text=Predictive%20AI%20algorithms%20empower%20farmers,of%20illness%20within%20the%20herd.
 - https://www.precision-livestock.com/




(2) A well-documented code file that you can run to demo your project. This can be a .py file, a Jupyter Notebook, or a link to a Colab. Make sure you can run the code during the presentation for a demo. You can demo code examples found on the internet, but you must cite the source.


(3) A link to an externally hosted website (e.g. a Google App Script site, a Google Sheets site) that you have built using GenAI (e.g. Claude) to demonstrate a simple idea related to your topic. If this is not possible for your topic, you can instead demo of the use of a well-chosen product.


(4) A project page for your group with a kanban board that looks like this that show a list of tasks that you have done, ongoing, and potential future development ideas as to-dos. Your team should use the project page during the semester to track your tasks and progress. You should be ready to discuss how you used the project board during your presentation.
