### Java Desktop Application - Technical Service

- This project is a technical service system project. A user who is the owner of a technical service company can control his customers, the products that need to be repaired and the delivery status of these products on this system.

- There is a User (company owner) entry for the system. The user who logs into the system can add, update and delete customers. It can add, delete and update the products belonging to the customer. Customer's products are examined in 4 cases. 0: The product to be repaired has been received from the customer. 1: The product is under repair. 2: The product has been repaired. 3: The product has been delivered to the customer. Products are listed in the interface according to these situations. At the top of the dashboard, our products that have been repaired and are waiting to be delivered to the customer (2nd state), that have just arrived at the service (at 0th state) at the bottom, and our products that have been repaired and delivered to the customer (3rd state) are listed on the page we call Archive.

### Languages, Technologies and Environments Used in this Project

| Java/JFrame  | OOP | SQLite | IntelliJ  |
| :------------: | :------------: | :------------: | :------------: |
|  <img src ="https://cdn.iconscout.com/icon/free/png-256/java-60-1174953.png" width ="100px" height = "100px" style="float:left" > | <img src ="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQie1pvA8p-kyK_bGjsjPJWv8x4NF9ahNvFA&usqp=CAU" width ="65px" height = "65px" style="float:left " >  |  <img src ="https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/Sqlite-square-icon.svg/1200px-Sqlite-square-icon.svg.png" width ="65px" height = "65px" style="float:left " > | <img src ="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/70px-IntelliJ_IDEA_Icon.svg.png" width ="65px" height = "65px" >  |


### Project Overview

<p>


| Login |
| ------------ |
| <a href="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/login.png" target="_blank"><img src="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/login.png" width="500" style="max-width:100%;"></a> |
  
| Dashboard |
| ------------ |
| <a href="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/dashboard.png" target="_blank"><img src="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/dashboard.png" width="500" style="max-width:100%;"></a> |
  
| CustomerAdd |
| ------------ |
| <a href="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/addCustomer.png" target="_blank"><img src="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/addCustomer.png" width="500" style="max-width:100%;"></a> |
  
| Services |
| ------------ |
| <a href="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/addService.png" target="_blank"><img src="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/addService.png" width="500" style="max-width:100%;"></a> |
  
| Archive |
| ------------ |
| <a href="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/archive.png" target="_blank"><img src="https://github.com/kardelentugay/java-desktop-technical-service/blob/main/images/archive.png" width="500" style="max-width:100%;"></a> |

</p>  


#### Packages, Classes and Interfaces
                
+ models
    + IUser
    + UserImpl
    + IDashboard
    + DashboardImpl
    + ICustomer
    + CustomerImpl
    + IService
    + ServiceImpl
    + IArchive
    + ArchiveImpl
+ props
    + User
    + Customer
    + Service
+ utils
    * DB
    * Util
+ views
    * Login
    * Base
    * Dashboard
    * CustomerAdd
    * Services
    * Archive
                    
### Demo Account
                    
 🔐 Email  | 🗝️Password
------------- | -------------
kardelen@mail.com  | 1234



### End
