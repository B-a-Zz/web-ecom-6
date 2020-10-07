# web-ecom-6
COURIER SERVICE APPLICATION DETAILS FOR DEVELOPMENT

Project name: Deliveco
This is a delivery web application for transporting cargo, parcels or goods to
customers. Customers should oversee parcel packaging. Deliveco will offer
parcel transport and secure storage depots for the delivery process from city to
city and within the same city in any country.
A simple white and blue theme, or white and sky-blue theme will suffice.
We are considering a UX/UI and the APIs for backend services. Normal pages
about website like
1. Index
2. contact or chat bot
3. About
4. Privacy policy
5. Terms of service
Will be added as in normal website the preliminary website
Backend services to consider are:
1. User management service
2. Booking service
3. Payment service
4. Delivery service
5. Messaging service
6. Customer support service
User management service may include but is not limited to the following tasks:
1. Login
2. Signup
3. Profile
4. forget password
5. user verification or authentication usually using valid ID Card.
6. My dashboard
In this line, the suggested user roles are users (sender and receiver), drivers and
website admins.
Question: should a user have more than one role? E.g. I am a driver, a user and
an admin
Booking service is used to manage the process of booking a parcel in for delivery.
The user will need to choose the destination depot and how to send the parcel to
the depot - either to take to nearest depot or ask our driver to pick up. Tasks here
include but are not limited to:
1. Book delivery
2. view booking
3. cancel booking
4. edit booking
5. change booking status.
Booking status can include the following:
1. received
2. accepted
3. awaiting payment
4. payment confirmed
5. parcel received
6. and booking confirmed.
Payment service: This may also be referred to as billing service. It encompasses
tasks involving customer billing and paying drivers. These tasks include but are
not limited to the following:
1. booking bills calculator
2. view booking bill
3. make payment
4. view payment
5. print receipt
6. View my pay (driver)
7. get my pay(driver)
8. view all my pay(driver)
Delivery service: This API shall handle all processes involving parcel delivery
once Deliveco has confirmed delivery booking. Tasks here include but are not
limited to the following:
1. View delivery route (Admin)
2. Track parcel (user, admin)
3. Broadcast jobs to drivers (admin)
4. Accept jobs (driver)
5. View my jobs(driver)
6. Update parcel status (driver)
7. Confirm delivery (user, driver)
8. Complete delivery and close (admin)
Examples of parcel status can be:
1. At depot (depot number, town and
1. At depot (depot number, town and city)
2. Dispatched to depot
3. Dispatched for delivery (address)
4. Delivered
5. Confirmed
6. Closed
Messaging service: Text messaging during entire life cycle of delivery process
and notification menu on website.
Customer support is for admins to attend to issues from customers. It can
include chat, FAQ among others.
Considerations
Google maps usage for addresses
Using travel distance or Time taken for bil
