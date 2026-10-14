ATRACADORE CINEMA 🎬

A desktop cinema browsing and ticketing application built with C++ and the Qt framework.

📖 About the Project

I created ATRACADORE CINEMA as a personal project to practice building both front-end user interfaces and back-end logic in C++. My main motivation was to step away from basic exercises and build a complete, practical, and useful application from scratch.

✨ Features

The application currently supports the following functional features:

* **Movie Catalogs:** Browse dedicated "Now Playing" and "Coming Soon" sections.
* **Detailed Information:** View movie synopses, promotional banners, cast lists, and producer details.
* **Personal Watchlist:** Save specific movies to a dedicated watchlist to keep track of what you want to see.
* **Showtime & Seat Selection:** Choose from multiple showtimes (3pm, 6pm, 8pm, 10pm) and select specific seats using an interactive visual theater grid.
* **Ticket Purchasing & Invoicing:** Simulate a ticket purchase (fixed at 500 DOP). Upon purchase, the app automatically generates a detailed `.txt` receipt and saves it directly to your computer's Desktop.

💻 Technologies Used

* **Language:** C++
* **Framework:** Qt (Qt Widgets, QtCore, QtGui)
* **Build System:** CMake

🚀 Getting Started

You do not need to compile the code to try out the application.

1. Go to the release section of this repository.
​2. Download the latest `.zip` file containing the application.
3. Extract the folder and run the `.exe` file.

*(Note: The executable has been packaged with all necessary Qt dependencies using `windeployqt`, so it is ready to run right out of the box).*

🧠 What I Learned

One of the biggest challenges—and the most valuable learning experience—was coordinating the classes and designing the entire user interface programmatically. Because I did not use a visual drag-and-drop designer, placing and styling widgets required writing the code and then executing the application after every single change just to verify the visual layout and pixel coordinates. This heavily improved my understanding of UI structure, event handling, and C++ class coordination.

🔮 Future Improvements

This project was built as a foundation. While it is fully functional for its current scope, it was designed with scalability in mind and can be modified in the future to add a variety of missing features, such as database integration for dynamic movie loading or user authentication.

👤 Author

Darian Diaz

 GitHub: [@DarianDP](https://github.com/DarianDP)


*If you want to compile the project yourself, clone this repository and open the `CMakeLists.txt` file in Qt Creator.*
