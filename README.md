# Boris_Bike
### [Makers Academy](http://www.makersacademy.com) - Week 1 Pair Programming Project

This is a program designed to let a user rent a bike by using multiple payment systems via a docking station.

The docking station can accept payments, release and dock a bike, and can check the status of the bike.

The learning objectives for this week were:

- Test Driven Development (TDD) using RSpec
- Follow an appropriate debugging process to 'tighten the loop' and 'gain visbility' when faced with bugs
- Basic class structure and attributes


### User Stories

```
As a person,
So that I can use a bike,
I'd like a docking station to release a bike.
```

```
As a person,
So that I can use a good bike,
I'd like to see if a bike is working
```


### User Stories Table Representation

| Objects            | Messages          |
| ------------------ | ----------------- |
| Person             |                   |
| Bike               | working?          |
| DockingStation     | release_bike      |



### User Stories Diagram

(Person) working? ---> (Bike) <--- release_bike (DockingStation)
