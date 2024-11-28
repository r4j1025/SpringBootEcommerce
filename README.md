
# Simple E-Commerce Website

This project is a basic **E-Commerce Website** built using **React** for the frontend and **Spring Boot** for the backend. It integrates an **H2 JPA database** to handle data storage and offers essential e-commerce functionalities like adding products (with images) and performing advanced searches.

## Features
- **Product Management**  
  - Add new products along with images.
  - View all available products.
- **Advanced Search**  
  - Search products using various filters and criteria.
- **Responsive Design**  
  - User-friendly interface adaptable to different screen sizes.
- **In-Memory Database**  
  - Uses **H2 Database** for lightweight and efficient data handling during development.
- **Modern Tech Stack**  
  - React and Spring Boot integration for seamless frontend-backend communication.

## Tech Stack
### Frontend
- **React.js**  
  - For building a dynamic and interactive user interface.
- **Axios**  
  - For making API calls to the backend.
- **CSS**  
  - For styling the application.

### Backend
- **Spring Boot**  
  - For handling the backend logic and REST APIs.
- **Spring Data JPA**  
  - For database interaction and ORM.
- **H2 Database**  
  - In-memory database for storing data during development.

## Installation and Setup
### Prerequisites
- **Node.js** and **npm** (for frontend)
- **Java JDK** (for backend)
- An IDE like IntelliJ IDEA, Eclipse, or Visual Studio Code.

### Steps to Run the Project
 **Clone the Repository**
   ```bash
   git clone https://github.com/r4j1025/SpringBootEcommerce.git
   cd SpringBootEcommerce
   ```


 **Run the Frontend**  
   - Navigate to the `frontend` folder:  
     ```bash
     cd client
     ```
   - Install dependencies and start the React app:  
     ```bash
     npm install
     npm run dev
     ```
   - The frontend will start at `http://localhost:3000`.

### Configuration
- **H2 Database Console**:  
  Access it at `http://localhost:8080/h2-console`. Update the connection URL, username, and password if needed in the `application.properties` file.

- **Backend API Endpoints**:
  - Add Product: `POST /api/products`
  - Get All Products: `GET /api/products`
  - Search Products: `GET /api/products/search?keyword=...`
  - ...

## Screenshots

## Future Enhancements
- Add user authentication and authorization.
- Implement cart and order management features.
- Integrate with an external database like MySQL or PostgreSQL for production use.
- Add support for image uploading to cloud storage (e.g., AWS S3).

## License
This project is licensed under the [MIT License](LICENSE).

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you want to improve this project.

Let me know if you need adjustments!
