# PIoT Assignment 3 (Distinction) - semester 1 2020 at RMIT

We were asked to develop a system for a rental car service with Raspberry Pis and ultilise Google Cloud APIs

## Requirements

### Customer

- Be able to register and login
- Input validation scheme
- View car rental history
- Search with filters and view all available cars (with locations)
- Book/Cancel a booking via the system
- Add/Remove events in Google Calendar
- Unlock/lock a car with Raspberry Pi (including login with facial recognition)

### System Admin

- Login
- View car rental history (for all user)
- Search users and cars
- Edit info about users and cars
- Report cars with issue (so the engineer can fix it)

### Company Manager

- Login
- A visualization dashboard (3 types of any):
  - Line chart
  - Pie chart 
  - Bar chart
  
 - The charts need to indicate business status to help decision making:
    - Daily active users
    - Percentage of usage for each car per day
    - Which day in the week that has the most booking

### Engineer

- Login 
- Be able to receive notification from the System Admin about the car that needs to be repaired
- Check the car's location via website
- Automatically unlock car via Bluetooth
- Be able to have their QR code scanned

## Dependencies

- Raspberry Pi
- Flask API
- OpenCV
- Pybluez
- Google Cloud APIs (Calendar, Maps, SQL, Data Store, etc.)
- Pushbullet API
- Sphinx Documentation

## Team members

- Thach Ngoc Nguyen - s3651311
- Fahim Tahmeed – s3680881
- Vinh Ngo Gia - s3578687
- YiNong Xu - s3770071

## Contribution Report

Can be found at `/root/PIOT A3 Contribution Report.pdf`

