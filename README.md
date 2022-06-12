# 02-Venue-Booking-System

## Introduction
The rooms A101, A102 and Auditorium are available for booking. Some current bookings are also taken in those rooms. Based on the given json data for current bookings, two functions have been created in this test. The purpose of the first function is to check the room is available for booking. The purpose of the second function is to display all current bookings that occur today, this week and next week for a room.

## Table of Contents
* [Detailed Description](#detailed-description)
* [Technologies](#technologies)
* [Setup](#setup)

## Detailed Description

Two problems have to be solved for this test based on the given current bookings json data.  

For the first problem, a function for checking the room is available for booking has created. The room can be available when there is no current booking during requested start time and end time. In the function, the roomId, startTime and endTime are accepted as parameters. Then the given current booking data is being filtered and the conditional statements among the filtered current booking data and the inputted parameters are created. Based on the data, true will be returned if the inputted parameters are available for booking and false will be returned if not. Finally, the returned result is passed to the HTML in order to show the result in browser.  

For the second problem, a function that returns all current bookings that occur today, this week and next week for a room has created. The roomId is accepted as a parameter. Today date, the start date of this week, the end date of this week, the start date of next week and the end date of next week are set up as the variables and their values are given using javascript date formats. Then the given current booking data is filtered. And then the conditional statements among the startTime and endTime of filtered data and today date, start date and end date of this week, and start date and end date of next week are created. The filtered startTime and endTime are also formatted to get the date only, not including time. Because time has to be ignored to return the required booking data. The function returns the array and  finally, the returned result is passed to the HTML in order to show the result in browser.

## Technologies
* HTML
* Javascript

## Setup
* The working demo can be seen here https://nwaenandaraung.github.io/02-Venue-Booking-System/
* The parameters can be changed as requried in the corresponding function.
