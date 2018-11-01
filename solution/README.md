# Solution 

## - Analyze and understand the problem 👨‍💼

### problem statment ⁉️
Fehrnana, the IT manager in HanaMantana Inc., is facing a tedious task. She has more than 150 different IT assets. She needs to register them in a registrar. In addition to the asset registrar, Fehrnana would like to schedule asset regular checks with preventive maintenance. Assets are classified into three classes (annually, quarterly, monthly). Each class has its own preventive maintenance frequency. Fehrnana would like the maintenance history for every asset along with maintenance report for every preventive maintenance event.

### Analyze and understand the problem  📝

- Fehrnana have more than 150 different IT assets (Machine,Hardware,Software and other)

#### She needs 👩‍💼 
- register assets in a registrar
- register In addition to the asset registrar
- schedule asset regular checks with preventive maintenance
(annually, quarterly, monthly)
- maintenance history for every asset 
- maintenance report for every preventive maintenance event.

### Solution steps 💡💡

- we need to building form to help Fehrnana ✍  register assets in asset registrar.

Using Zoho <br /> 
1️⃣  Create a new form and select an Blank Form   <br /> 
2️⃣  Name Form to IT Asset Registrar | ` IT_Asset_Registrar ` <br /> 
3️⃣  Add Asset Fields 
- Maintenance By * (assign who will maintain this asset)
- Asset Type * (classify the asset )
- Machine Type 
- OS
- Mobile OS
- Hardware Type
- Software Product
- Describe this asset
- Asset Address <br /> 


4️⃣ Add actions are executed on various events in the form `IT_Asset_Request`, while a record is being created or edited <br /> <br />
![Add actions](./img/add_action.gif?raw=true "Add actions")  <br /> <br />

