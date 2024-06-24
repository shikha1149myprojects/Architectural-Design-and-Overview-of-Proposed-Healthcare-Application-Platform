Scenario Overview: 
 

Your group has provided an overview and assessment the security vulnerabilities in a healthcare company's cloud infrastructure. Based on your midterm submission, please provide a high level overview of the infrastructure changes that you would recommend based in your midterm deliverables. Your group will be responsible for providing documentation on the services and methodologies that you intend to employ to mitigate the security risk that you have identified in the various assessment reports. Your deliverable should include an architectural diagram that provides a high level overview of your proposed architecture. This diagram should include accurate dataflows that cover three scenarios. 

The first scenario is from the patient's point of view. The patients will access the portal from personal devices and will participate in telemedicine consultations as well as accessing test results, scheduling appointments and general inquiries.
The second scenario is from the care providers point of view. They will have access to all patients data as well as the ability to send and receive messages from third parties including hospitals
The third scenario is from the IT support point of view. The IT team may have several roles including end user support, DBAs, system administrators and super admins.
Your technical overview and diagrams should cover the basic application and additional cloud services and tools that will be used to mitigate the identified risks. The level of detail of your diagram should closely resemble your technical overview.

The application stack consists of the following components:

Web servers: These serve the frontend of the website and handle user requests.
Application servers: These handle the business logic and process user requests.
Database servers: These store product information, user details, and medical history.

 

Infrastructure Details:
 

Cloud Provider: The healthcare company uses a popular cloud service provider (e.g., AWS, Azure, Google Cloud) for hosting its infrastructure.
Data Storage: Patient records, medical images, and other sensitive healthcare data are stored in cloud-based databases and file storage systems.
Virtual Machines (VMs): The company utilizes VMs for hosting healthcare applications and databases.
Network Configuration: The cloud infrastructure has several virtual networks and subnets for different departments and services within the company.
Identity and Access Management (IAM): The healthcare company employs IAM policies and access controls for managing user access to cloud resources.
The IT department requires full access to both frontend and backend instances for management purposes.
All instances should be automatically assigned public and private IP addresses where necessary
The VPC should be designed to accommodate future growth and scalability.
