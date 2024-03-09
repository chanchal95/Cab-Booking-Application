<h2>Technologies used</h2>
Java SpringBoot

<h2>Salient features</h2>
1-Robust Exception Handling is done for all API endpoints
2-Prevents creation of users or drivers with the same phone number
3-Separation of concerns divides the application into different parts: Controllers, Services, Repository.
4-Loose coupling is ensured by using Dependency Injection.
5-Clean code is written by using proper variable names and comments wherever necessary. Code reusability is also taken into account. New features can easily be accomodated.
6-Almost everything is implemented according to the business requirements provided. The differences present are only there to make the application more durable and scalable.

<h2>List of API endpoints</h2>
<h3>User related</h3>
1- add_user(String userName, long userPhoneNumber, long xCoordinate, long yCoordinate)
2- update_user(long userPhoneNumber, String userNewName, long userNewPhoneNumber)
3-update_userLocation(long userPhoneNumber, long xCoordinate, long yCoordinate)

<h2>Driver related</h2>
1-add_driver(String driverName, String driverGender,  long driverAge, long driverPhoneNumber,  String vehicleDetails, long xCoordinate,  long yCoordinate, boolean available, long driverEarning)

2-update_driverLocation(long driverPhoneNumber, long xCoordinate, long yCoordinate)

3-change_driver_status(long driverPhoneNumber, boolean available)
find_total_earning()


<h3>Ride related</h3>
1-find_ride(long userPhoneNumber, long sourceXCoordinate, long sourceYCoordinate, long destXCoordinate, long destYCoordinate)
2-choose_ride(long userPhoneNumber, long driverPhoneNumber)
3-calculateBill(long userPhoneNumber)


