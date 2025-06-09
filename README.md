# airfare-search-agent
Airfare Search Agent
A React-based web application for searching and comparing flight prices across multiple airlines and routes.
Project Structure
airfare-search-agent/
├── README.md
├── package.json
├── .gitignore
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   └── AirfareSearchAgent.jsx
│   ├── App.js
│   ├── App.css
│   └── index.js
└── docs/
    └── screenshots/
Features

Universal Route Search: Search flights between 25+ major airports
Flexible Trip Options: Round-trip or one-way flights
Price Comparison: Results sorted by lowest price
Flight Details: Duration, stops, departure/arrival times
Search History: Track recent searches
Responsive Design: Works on desktop and mobile devices

Supported Airports
East Coast

Washington DC Area: IAD (Dulles), DCA (Reagan), BWI (Baltimore)
New York Area: JFK, LGA (LaGuardia), EWR (Newark)
Other: BOS (Boston), PHL (Philadelphia), ATL (Atlanta), MIA (Miami), MCO (Orlando), CLT (Charlotte)

West Coast

California: LAX (Los Angeles), SFO (San Francisco), SJC (San Jose)
Other: SEA (Seattle), PHX (Phoenix), LAS (Las Vegas), DEN (Denver)

Central US

Texas: AUS (Austin), DFW (Dallas), IAH (Houston)
Other: ORD (Chicago O'Hare), MDW (Chicago Midway), MSP (Minneapolis)

Technology Stack

Frontend: React 18 with Hooks
Styling: Tailwind CSS
Icons: Lucide React
State Management: React useState
Build Tool: Create React App

Installation

Clone the repository:

bashgit clone https://github.com/AgenticWorkload/airfare-search-agent.git
cd airfare-search-agent

Install dependencies:

bashnpm install

Start the development server:

bashnpm start

Open http://localhost:3000 in your browser

Usage

Select Route: Choose departure and destination airports from dropdown menus
Swap Route: Use the swap button to reverse departure/destination
Choose Dates: Select departure date and return date (for round-trip)
Set Passengers: Choose number of travelers (1-6)
Search: Click "Search Flights" to find available options
View Results: Browse flights sorted by price with detailed information

API Integration
The current version uses mock data for demonstration. To integrate with real flight APIs:
Recommended APIs:

Amadeus Global Distribution System
Skyscanner Partner API
Google Flights API
Individual Airline APIs (Southwest, American, United, Delta)

Implementation Notes:

Replace mockSearchResults() function with actual API calls
Add API key management and rate limiting
Implement error handling for API failures
Add loading states and retry mechanisms

Contributing

Fork the repository
Create a feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request

Future Enhancements

 Real-time API integration
 Price alerts and notifications
 Multi-city trip planning
 Seat selection and preferences
 Booking integration
 Calendar view for flexible dates
 Filter by airline, stops, departure time
 Price history and trends
 Mobile app version
 User accounts and saved searches

License
MIT License - see LICENSE file for details
Support
For support, please open an issue on GitHub or contact the development team.

Note: This is a demonstration interface. For production use, integrate with actual flight booking APIs and implement proper security measures.
