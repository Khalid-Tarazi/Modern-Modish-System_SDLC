One of the key aspects of managing and developing a system is to track the software requirements throughout the SDLC. This way, the final product will match the initial requirements and satisfy the user. This is how we can track the software requirements from start to finish in Modern Modish System:

I.	**Planning**: In this phase, we establish the project’s scope and collect the system’s initial requirements. For the Modern Modish System, this means identifying the inventory management, sales tracking, customer relationship management, and other functional and non-functional requirements. This involves conducting stakeholder meetings to identify high-level needs, defining project goals, and outlining potential risks and constraints. 
For instance, A high-priority requirement might be an effective inventory management system to monitor inventory stock levels and streamline order processing. Requirements are documented and act as a reference throughout the entire software development lifecycle.

II.	**Analysis**: We examine the functional and non-functional requirements of our new system in depth to create more specific technical requirements. This means determining the exact features of the inventory management system, the data fields for customer relationship management, and so on. We then check that these refined requirements are consistent with the initial ones.
Then we break down the functional/non-functional requirements into detailed functionalities through interviews, feedback, and continuous validation. For example, Regarding the Modern Modish System, an in- depth specification could be derived from the inventory management requirement; the system must provide real-time updates of inventory levels, set off notifications for low stock, and produce automatic reorder proposals based on previous sales statistics.

III.	**Design**: In this phase, we design the system’s architecture based on the technical requirements. Each part of the design should correspond to a specific requirement. For instance, the design of the database schema should relate to the requirements for inventory management and customer relationship management.
This consists of developing database schemas, interfaces, and data flows in addition to designing system structural diagrams. Every element of the design should directly address a particular requirement. For example, the database schema can contain tables for customer profiles, purchase histories, and communication logs in response to the requirement for customer feedback based on the service they used.

IV.	**Implementation**: During the implementation phase, we develop the system according to the design phase. Each piece of code can be linked to a specific part of the design phase, which in turn can be linked to a specific requirement. This linkage ensures that all requirements are covered in the development process.
For instance, if the requirement is for customers to explore and customize their furniture item, the implementation would involve developing a module that allows customers to access and browse all the furniture items available and registered in the database and modify them as needed.

V.	**Testing**: We test the system to make sure it meets the requirements. We could use test cases; each test case should be connected to a specific requirement. Test cases are developed based on individual requirements, covering functionality, integration, and system testing. We can also create a requirements traceability matrix to track the tested functional and non-functional requirements as needed, then we can track the changes.
For example, a test case directly connects to the functional requirement of letting customers log in through the system by email and password. By running this test case, we can verify whether or not the system satisfies this requirement. In the event that the test case is not successful the login feature has failed and has to be addressed. then it can be connected to the unfulfilled requirement.

VI.	**Maintenance**: After deployment, we will need to maintain and update the system regularly. Any changes or additions to the system should be linked to new or changed requirements. This link ensures that changes are in line with the customer’s needs and that the system keeps meeting its requirements as intended.
For example, to keep the system in line with user expectations, any modifications that are made in response to a new requirement—like integrating a loyalty program—would be tied to it.

---

## ~ Functional Requirements Tracing ~

Functional requirements define the specific behavior or functions of the system. For the Modern Modish System, these requirements can be tracked as follows:

¤	**User Authentication**: We can track this requirement by testing the login feature and making sure it works as expected. This requirement allows customers to log in through the system by email and password.

¤	**Personalization**: This requirement for customers to explore and personalize furniture items is traced by monitoring user interactions and feedback.

¤	**Product Display**: We can track this functional requirement by evaluating the user interface and making sure the categories are properly displayed. This requirement shows furniture items in different categories.

¤	**Ordering and Payment**: The requirement for customers to place orders and securely pay for them is tracked by conducting transaction tests.

¤	**Order Tracking**: We can trace this requirement by testing the order tracking system. This requirement lets customers track their orders.

¤	**Feedback System**: The functional requirement for customers to rate services and provide feedback can be tracked by reviewing the feedback received.

¤	**Inventory Tracking**: For shipment employees to track inventory, we can trace this requirement by reviewing the inventory reports.

¤	**Stock Notification**: We can trace this requirement by testing the notification system. This requirement notifies shipment employees when stock is low.

¤	**Reporting**: The requirement for generating reports and analytics is tracked by reviewing the generated reports and ensuring they provide the necessary information.



## ~ Non-Functional Requirements Tracing ~

Non-functional requirements define the system’s properties or characteristics. these requirements can be traced as follows:

¤	**Security**: The security measures requirement for protecting payment information can be tracked by conducting security audits and penetration tests.

¤	**Performance and Reliability**: We can track this requirement by performing stress tests and monitoring system performance.

¤	**Scalability and Flexibility**: This requirement is traced by monitoring the system’s ability to handle increased loads and adapt to changes.

¤	**User-Friendliness and Accessibility**: It is tracked by conducting user experience studies and accessibility audits.

¤	**Maintainability and Modularity**: By reviewing the system’s architecture and codebase, and monitoring the ease of testing, debugging, and updates.
