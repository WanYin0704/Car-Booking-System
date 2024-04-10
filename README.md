# Car-Booking-System
<img align = "right" src="https://github.com/WanYin0704/Car-Booking-System/assets/146581747/24274eb7-5b89-461c-b136-7424797d455d" width="400" length="200" height="225">

**SpeedyCar** (Car Booking System) is intended to make booking a car through the system as simple as possible for
users. There are altogether two categories of users-**administrators, and customers**, involved in
this system. If **_customers_** want to book a car but do not have an account in the system, they need
to register first. **_Customers_** must fill out personal information such as their identification number,
full name, address, contact number, license number, and password, and confirm the password for
validation checks when registering. They can also modify their details if there are any details that
they want to modify. 

There is an option for customers to change their account password.
**_Customers_** can book any car offered through the system by inputting the pickup and return dates.
The system will automatically generate the total price of the booking by calculating the number
of days customers have booked.
After the customer has booked a car, the _**admin**_ will then verify the status of the booking as
either "**approved**" or "**rejected**", depending on the availability of the car on the day the **_customer_**
booked it. _**Admin**_ is the one who has full authority to manage the system. He can add, modify,
and delete the vehicles in the system. Other than that, the _**admin**_ can view all the booking lists
made by customers. 

### Supplementary system features
- Encryption of password
- SQL Injection prevention
- Enhanced password security with double-field checks for registration and modification
- Rectify login error to prevent unauthorized access to other users' pages after login
- Addressing of booking error to prevent return dates earlier than pickup dates




