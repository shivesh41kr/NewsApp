# NewsApp

NewsApp is a full-stack application taken Reference from Harvard Business Review website for managing and displaying news articles. It is built with Django on the backend and React on the frontend.

## Preview
![download](https://github.com/user-attachments/assets/b1e80484-330e-4fc7-aca9-ab361334f543)
![Screenshot from 2024-07-16 11-24-31](https://github.com/user-attachments/assets/bd385030-62f1-4a2e-ae94-ad0f07dbd901)
![Screenshot from 2024-07-14 13-59-58](https://github.com/user-attachments/assets/8e3ee51e-69e4-4857-ba8f-83227ab0ed3c)
![Screenshot from 2024-07-15 18-30-09](https://github.com/user-attachments/assets/098dd37d-dad6-4d69-a939-f668c87cc2e4)
![Screenshot from 2024-07-23 16-22-48](https://github.com/user-attachments/assets/4f51d41f-2b57-413b-934a-abac6cc23a12)



## Project Structure

- **Front-End/**: Contains the React frontend of the application.
- **apis/**: Backend API implementation for the application.
- **django_news/**: Main Django project configuration and settings.
- **media/**: Folder for storing media files like images and videos.
- **modules/**: Custom modules and functionalities for the application.
- **newsApp/**: Core application logic, including models, views, and templates.
- **static/**: Static files such as CSS, JavaScript, and images.

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x
- Node.js & npm
- SQLite3 (or any other database if configured)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/newsApp.git
    cd newsApp
    ```

2. **Install backend dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Install frontend dependencies:**
    ```bash
    cd Front-End
    npm install
    ```

4. **Apply migrations:**
    ```bash
    python manage.py migrate
    ```

5. **Run the development servers:**

    - **Django Backend:**
      ```bash
      python manage.py runserver
      ```

    - **React Frontend:**
      ```bash
      cd Front-End
      npm start
      ```

### Usage

- Access the frontend at `http://localhost:3000`.
- Access the backend API at `http://localhost:8000/api/`.

### Contributing

Feel free to submit issues and enhancement requests.

### License

Distributed under the MIT License. See `LICENSE` for more information.
