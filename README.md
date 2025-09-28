# Workshop_3

## Developers

| Name                  | Role                  | GitHub Handle     | Email                  |
|-----------------------|-----------------------|-------------------|------------------------|
| Kanwar Singh Sandhu   | Backend               | @kanwar911        | kssandhu23@myseneca.ca |
| Krish Jitesh Gohil    | Frontend              | @Krish-Gohil      | kjgohil@myseneca.ca    |
| Shashank Nanda        | Full Stack            | @theshashanknanda | snanda9@myseneca.ca    |

# Project Name: Trip Sharing Mobile App

## Project Description

Planning group trips often becomes disorganized, with details scattered across multiple chat apps, spreadsheets, and emails. Friends may struggle to agree on dates, destinations, or budgets, and important updates are easily missed. The lack of a centralized system results in duplicated work, miscommunication, and last-minute confusion about itineraries, costs, or responsibilities.

## Solution

To address the challenges mentioned above, our solution is to develop Trip Sharing Mobile app that combines all the processes into a single, centralized platform. Users will have a shared group chat where they will be able to discuss ideas, and see all the available travel options, we will implement this using free APIs(namely sky scanner). We also plan to implement a voting system in the group chat which will allow users to collectively decide on key trip details.
Once a trip is finalized, the app will enable collaborative itinerary building, where multiple users can contribute e.g., one person adds hiking, while another adds skydiving to create a complete plan together. By combining all this, our app reduces confusion, and ensures that all the members are informed and engaged throughout the trip planning process.

## Technologies required
To bring the Trip Sharing Web App to life, we’ll use React.js on the frontend to create a responsive, user-friendly interface where group members can easily interact and plan their trips. The backend will run on Node.js with Express, handling the core logic, APIs, and authentication. All trip data—like user accounts, chats, itineraries, and activities will be stored in MongoDB, which gives us the flexibility to manage dynamic and collaborative content. To make the group chat and voting system run in real time, we’ll integrate WebSockets (Socket.io). For travel options, the app will connect to external services like Skyscanner’s free API. Authentication will be secured using JWT tokens or Firebase Authentication, and media such as images or receipts will be uploaded to cloud storage like AWS S3 or Firebase Storage. Finally, the app will be packaged with Docker for easy deployment and hosted on platforms such as AWS, Azure, or Vercel, ensuring it remains scalable and reliable as more users join.
