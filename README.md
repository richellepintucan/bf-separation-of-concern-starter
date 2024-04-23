# Flights

## Project definition

> This simple project provide users with access to information about available
> flights

## Table of contents

- [Flights](#flights)
  - [Project definition](#project-definition)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Code Examples](#code-examples)
  - [Features](#features)
  - [Status](#status)

## General info

> The objective of the project is to practice separation of concern in
> JavaScript.

## Screenshots

![Example screenshot](./assets/screenshot.png)

## Technologies

- JavaScript
- HTML5
- CSS3
- VSC code
- Jest

## Setup

Create a new repo from the template

1. Clone the repo from your GitHub account
   > git clone `HTTPS link`
2. Open Visual Studio Code
3. Run npm i
4. Open index.html

## Code Examples

```js
const data = {
	flights: [
		{
			id: 1,
			name: 'VQ-903',
			plane: 'ATR725',
			departureDate: '2023-08-05 13:45:00',
			origin: 'DAC',
			arrivalDate: '2023-08-05 14:40:00',
			destination: 'CGP',
			stops: 0,
		},
	],
};
```

## Features

List of features ready and Todos for future development

- Flight Listing: Display a list of available flights, including essential
  details such as departure and arrival airports, departure and arrival times,
  airlines, flight numbers, and prices.

- Sorting Functionality: Provide the ability to sort the list of flights based
  on different parameters such as price, departure time, arrival time, or
  duration.

- Flight Details: Offer users the option to view more detailed information about
  each flight

To-do list:

- Setup Development Environment
- Design User Interface (UI)
- Implementation of Separation of Concerns

## Status

Project is: completed
