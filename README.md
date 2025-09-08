# Student Photo Viewer

A simple web-based application to display student photos from a college database using roll numbers. Users can search by roll number prefix or full roll number and view multiple student photos with pagination support.

---

## Demo

![Demo Screenshot](https://github.com/Praveenadapa425/sample/blob/main/Screenshot.png)


---

## Features

- **Search Functionality:** Find student photos by **roll number prefix** (e.g., `23MH1A49`) or a **full roll number**.
- **Dynamic Display:** View individual student photos or an entire batch.
- **Skeleton Loading:** A loading animation is displayed while images are being fetched.
- **Lateral Entry (LE) Support:** The system automatically includes photos for Lateral Entry students.
- **Pagination:** Easily navigate through large batches of students with built-in pagination.
- **Responsive Design:** The user interface is simple and works well on different screen sizes.

---

## Technologies Used

- **HTML5:** Provides the foundational structure of the webpage.
- **CSS3:** Used for styling, creating a responsive layout with flexbox, and implementing skeleton loader animations.
- **JavaScript (ES6):** Manages user input, handles image validation, controls pagination, and dynamically renders the photos.

---


## 📁 Project Structure

```
student-photo-viewer/
  ├── index.html        # Main HTML file for the application's user interface
  ├── header.jpg        # Header image displayed at the top of the page
  ├── README.md         # Project documentation file
  └── screenshot.png    # Screenshot of the application for the README
```  


## Usage

1.  **Open the file:** Simply open `index.html` in your web browser.
2.  **Enter a roll number:** Type a **roll number prefix** (e.g., `23MH1A49`) or a **full roll number** in the input field.
3.  **Generate photos:** Click the **Generate Photos** button or press **Enter**.
4.  **View photos:** The student photos will appear in the container below. If there are more than 100 images, use the pagination buttons to navigate.

**Note:** The system only supports student batches from **2015 onwards**. Photos for earlier batches will not be displayed.

---

## How It Works

1.  **Input Validation:** The application first checks that the user has entered a valid roll number or prefix.
2.  **URL Generation:** It then constructs the unique image URLs based on the provided roll number pattern.
3.  **Image Validation:** Before displaying an image, the system validates that the URL points to an existing photo, preventing broken image icons.
4.  **Skeleton Loader:** A skeleton loading animation is shown to the user while the images are being fetched from the database, improving the perceived loading speed.
5.  **Pagination Logic:** The system is programmed to limit the number of photos to 100 per page and provides navigation controls for larger batches.
6.  **LE Conversion:** For batch searches, the application automatically converts regular roll number prefixes to include Lateral Entry student prefixes, ensuring all students are accounted for.

---

## Future Improvements

-   Add **search filters** for specific branches or academic years.
-   Implement **lazy loading** to optimize performance for very large batches.
-   Include **fallback images** to gracefully handle missing student photos.
-   Enhance the **UI/UX** with more modern card designs and animations.
-   Store **recent searches** for quick, one-click access.

---

## License

This project is intended for educational purposes and can be freely used or modifiy.
