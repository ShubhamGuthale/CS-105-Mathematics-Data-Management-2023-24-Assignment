# CS-105-Mathematics-Data-Management-2023-24-Assignment
ASSIGNMENT -

CS 105 Mathematics Data Management 2023-24
InterCity Express Trains(IET) Database Assignment 

Name - Guthale Shubham Vishnu
Roll No.- 22111072
Class - M.SC.Computer Science (II Year)

Created the database named Intercity_Express Train(IET) by observing the given information.
Based on the table names you provided,here is an outline of the tables along with their potential attributes :

1.Trips:
TripID (Primary Key)
RouteID(forein key)
TripDate
DriverName (forein key)
OnTime

2.Bookings:
BookingID (Primary Key)
AgentID (forein key)
RouteID (forein key)
TripDate
SeatsSold
ChildSeats
AdultSeats
SeniorCitizenSeats

3.Coaches:
CoachID (Primary Key)
TrainID (forein key)
LastServiceDate
Mileage

4.Commission:
CommissionID (Primary Key)
AgentID (forein key)
OnlineTicketBookingSites
MonthYear
Amount

5.Drivers:
DriverID (Primary Key)
DriverName
Phone
CityOfResidence

6.Passengers:
PassengerID (Primary Key)
PassengerName
TripCount
Age
Type

7.RouteOperatingDays: Normalized From The Route Table
RouteID
DayOfWeek

8.Routes:
RouteID (Primary Key)
Distance
BoardStation
ArrivedStation

9.Station:
StationID (Primary Key)
StationName
StationContact

10.Ticket:
TicketID (Primary Key)
PassengerID (forein key)
Price
(OnlineTicket,ThirdPartywebsites,App,Ticket Counter)    (forein key) ----
 
11.Trains:
TrainID (Primary Key)
TrainDriver (forein key)
TrainName
RouteID (forein key)
LiveLocation
T_MaintenanceStatus
