# sre-github-lab
Requirement Documentation for a Student Task Tracker
# Food Delivery System – Student Task Tracker Template

## Overview

The Hostel Servers Food Delivery System is a mobile-friendly application designed for hostel canteens. Currently, students place food orders by calling the canteen manager or visiting the canteen directly. The manager manually records student details, manages orders, and assigns available servers for delivery.

The proposed system aims to digitize and centralize the food ordering and delivery process. Students will be able to view the available menu, place food orders, provide hostel and room details, select a payment method, and track their order status. The canteen manager will manage menus and orders, while servers will handle assigned deliveries. The system aims to reduce manual work, ordering mistakes, delays, and inconvenience for students.

## Scope

- In scope: Student registration and login using name, hostel number, room number, and contact information.
- In scope: View available food items and their prices.
- In scope: Menu management, including adding, removing, and updating food items, prices, and availability.
- In scope: Students can select food items, specify quantities, and place orders.
- In scope: Record student information, selected food items, total price, hostel number, room number, order date/time, and payment method.
- In scope: Canteen manager can view, confirm, and manage incoming orders.
- In scope: Canteen manager can assign orders to available servers.
- In scope: Servers can view assigned orders and update delivery status.
- In scope: Students can track order status, including Pending, Preparing, Assigned, Out for Delivery, and Delivered.
- In scope: Support cash and online banking payment methods.
- Out of scope: Delivery outside the selected hostel block or hostel area.
- Out of scope: External delivery riders and long-distance delivery services.
- Out of scope: Restaurant or canteen discovery outside the hostel.
- Out of scope: Advanced GPS-based delivery tracking.
- Out of scope: Managing multiple external restaurants.
- Out of scope: Online payment gateway integration.

## Stakeholders

- Student/Hostelite: Primary user who registers, views the available menu, places food orders, provides hostel and room details, selects payment methods, and tracks order status.
- Canteen Manager: Responsible for managing the food menu, updating prices and availability, viewing and confirming orders, and assigning available servers.
- Server/Delivery Staff: Responsible for viewing assigned orders, checking student and delivery details, delivering food, handling payments, and updating delivery status.
- Project Maintainer: Responsible for maintaining the system, keeping requirements documentation accurate and up to date, and managing future changes.

## Functional requirements

- FR-01: The system shall allow students to register and log in using their name, hostel number, room number, and contact information.
- FR-02: The system shall allow the canteen manager to add, remove, and update food items, prices, and availability.
- FR-03: The system shall allow students to view the available food menu.
- FR-04: The system shall allow students to select food items, specify quantities, and place orders.
- FR-05: The system shall record order details, including student information, selected food items, total price, hostel number, room number, order date/time, and payment method.
- FR-06: The system shall allow the canteen manager to view, confirm, and manage incoming orders.
- FR-07: The system shall allow the canteen manager to assign pending orders to available servers.
- FR-08: The system shall allow servers to view their assigned orders and related delivery details.
- FR-09: The system shall allow servers to update the delivery status of assigned orders.
- FR-10: The system shall allow students to view order status updates at major stages of delivery.
- FR-11: The system shall support cash and online banking as payment methods.
- FR-12: The system shall maintain records of completed orders, including customer, order, delivery, and payment information.

## Nonfunctional requirements

- NFR-01: Students should be able to view the menu and place an order within 3 minutes.
- NFR-02: The canteen manager should be able to assign a pending order to an available server within 1 minute.
- NFR-03: A new student, manager, or server should be able to use the system with minimal assistance after a short introduction.
- NFR-04: The system shall store 100% of completed orders with customer, order, delivery, and payment information.
- NFR-05: The system should remain accessible when the hostel internet/network and canteen services are available.

## Acceptance criteria

- FR-01: Given a student provides their name, hostel number, room number, and contact information, registering successfully creates an account that can be used to log in.
- FR-02: Given the canteen manager adds a new food item with its price, the item appears in the menu. Updating its price or availability reflects the changes in the menu.
- FR-03: Given food items are available in the menu, opening the menu displays the available items and their prices.
- FR-04: Given a student selects food items and specifies quantities, placing the order successfully creates a new order.
- FR-05: Given a student places an order, the system records the student details, selected items, quantities, total price, hostel number, room number, order date/time, and payment method.
- FR-06: Given new orders have been placed, the canteen manager can view their details and confirm them.
- FR-07: Given a pending order and an available server, assigning the order makes it visible in that server's assigned orders.
- FR-08: Given a server has an assigned order, the system displays the student's name, hostel number, room number, ordered items, and payment method.
- FR-09: Given a server has an assigned order, updating its delivery status changes the status displayed by the system.
- FR-10: Given an order moves through its delivery stages, the student can view its current status: Pending, Preparing, Assigned, Out for Delivery, or Delivered.
- FR-11: Given a student places an order, the system allows the student to select cash or online banking as the payment method.
- FR-12: Given an order is completed, the system stores its customer, order, delivery, and payment information.

## Assumptions and open questions

Assumptions

- A-01: The system will operate within a selected hostel block with a centralized shared canteen.
- A-02: Students, the canteen manager, and servers will have access to devices and an internet/network connection.
- A-03: Servers will be available within the hostel area to deliver food orders.
- A-04: Students will provide correct hostel and room information.
- A-05: Cash and online banking will be the supported payment methods.
- A-06: Online banking payments may only be recorded in the system if direct payment gateway integration is not implemented.

Open Questions

- Q-01: Which specific online banking methods will be supported?
- Q-02: How will the system verify that a server is available for a new delivery assignment?
- Q-03: Should students be allowed to cancel an order after it has been confirmed?
- Q-04: Who will be responsible for updating server availability?
- Q-05: What devices and network environments will be used to test system performance?

## Project status and viewing

Documentation only. The project vision and high-level requirements have been prepared. Application implementation has not started.