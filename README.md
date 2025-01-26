## **✈️ Flight Ticket Booking System**

---

# **Flight Ticket Booking System** 🛫  
The **Flight Ticket Booking System** is a simple yet interactive application designed for users to search flights, book tickets, and manage bookings—all without requiring a database. The project is built with **Python** for backend processing and **HTML** for the user interface. The system stores all data temporarily in memory, making it lightweight and ideal for smaller-scale applications or learning purposes.  

This project is a great starting point for developers interested in learning the basics of Python web development and HTML integration.

---

## **Features** 🚀  

### 1. **Search Flights** 🔍  
- Users can search for flights by specifying:  
  - Origin  
  - Destination  
  - Travel Date  
- The system displays matching flight options dynamically.  

### 2. **Book Tickets** 🎫  
- After selecting a flight, users can proceed to book tickets.  
- Booking includes real-time seat availability checks.  
- A confirmation message is displayed upon successful booking.  

### 3. **Dynamic In-Memory Storage** 📋  
- Data for flights and bookings is managed in memory using Python data structures like dictionaries and lists.  
- All data resets when the system is restarted (no persistent storage).  

### 4. **Lightweight Design** 💻  
- Simple and clean user interface using **HTML** and **CSS**.  
- Optimized for quick loading and intuitive user interaction.  

### 5. **Future-Ready Codebase** 🔧  
- The modular design allows for easy integration of additional features like payment systems or persistent storage in the future.  

---

## **Technologies Used** 🛠️  

### **Frontend**  
- **HTML**: For structuring the user interface.  
- **CSS**: For styling and layout design.  

### **Backend**  
- **Python**: Core logic for flight search and ticket booking.  

### **Storage**  
- **In-Memory**: Temporary storage using Python dictionaries and lists.  

---

## **Installation and Setup** ⚙️  

### **Prerequisites**  
Before running the system, ensure you have the following installed:  
- **Python**: Version 3.7 or higher.  
- A modern **web browser** (e.g., Chrome, Firefox, Edge).  

### **Steps to Run the Application**  

1. **Clone the Repository**  
   Clone the project repository to your local machine using:  
   ```bash  
   git clone https://github.com/satyayanamadal/flight-ticket-booking-system.git  
   cd flight-ticket-booking-system  
   ```  

2. **Run the Backend Script**  
   Start the Python backend by running:  
   ```bash  
   python flight.py  
   ```  

3. **Access the Application**  
   - **Option 1**: Open the `index.html` file directly in your browser.  
   - **Option 2** (if using Flask): Navigate to `http://127.0.0.1:5000` in your browser.  

---

## **Usage Instructions** 🌟  

### **1. Searching for Flights**  
- Open the application.  
- Enter your travel details in the search form:  
  - Origin city or airport.  
  - Destination city or airport.  
  - Travel date.  
- Click "Search Flights" to view available options.  

### **2. Booking a Flight**  
- Select a flight from the search results.  
- Proceed to book your ticket.  
- Confirm the booking details and submit.  

### **3. Confirmation**  
- Upon successful booking, a message will display your ticket details.  
- You can take a screenshot or note down the ticket information.  

---

## **Folder Structure** 📁  
```  
flight-ticket-booking-system/  
│  
├── flight.py         # Main Python script (backend logic)  
├── index.html        # Main HTML file (frontend interface)  
├── static/           # Optional folder for CSS or JavaScript files  
└── README.md         # Project documentation (this file)  
```  

---

## **How it Works** 🔍  
1. The **Python script (`flight.py`)** manages all backend operations, such as handling user inputs, searching flights, and managing bookings.  
2. The **HTML file (`index.html`)** serves as the user interface, where users interact with the system.  
3. Data is stored temporarily in memory using Python's dictionaries and lists, making the system fast and lightweight.  
4. Since no database is used, all data is lost when the application is stopped.  

---

## **Future Enhancements** 🔮  

This system can be expanded in several ways:  

1. **Persistent Storage**  
   - Use **JSON**, **SQLite**, or **MySQL** to store flight and booking data.  
   - This will allow data retention even after restarting the application.  

2. **Payment Gateway Integration** 💳  
   - Add support for secure online payments using gateways like **PayPal** or **Stripe**.  

3. **Mobile-Friendly UI** 📱  
   - Enhance the interface with responsive design for seamless mobile use.  

4. **User Registration**  
   - Allow users to create accounts and manage their bookings.  

5. **API Integration**  
   - Integrate with third-party APIs to fetch real-time flight availability.  

6. **Advanced Search Options**  
   - Add filters for price, flight duration, and preferred airlines.  

7. **Internationalization** 🌍  
   - Support multiple languages and currencies for global users.  

---

## **Contributing** 🤝  
Contributions are welcome! If you would like to improve this project, follow these steps:  

1. Fork the repository.  
2. Create a new branch for your feature or bug fix.  
3. Commit your changes and push the branch.  
4. Open a pull request, and describe your changes.  

---

## **License** 📄  
This project is licensed under the **MIT License**. You are free to use, modify, and distribute this code as long as proper attribution is provided.  

---

## **Contact Information** 📬  
For feedback, questions, or contributions, feel free to contact:  
- **GitHub**: [Flight Ticket Booking System](https://github.com/satyayanamadal/flight-ticket-booking-system.git)  

---

Happy Booking! 🛩️
