
---

## Usage

1. Open `index.html` in a web browser  
2. Enter a **roll number prefix** (e.g., `23MH1A49`) or **full roll number** in the input field  
3. Click **Generate Photos** or press **Enter**  
4. The student photos will be displayed in the container below  
5. Use the pagination buttons at the bottom to navigate through batches of students (if more than 100 images)  

**Note:** The system only supports batches from 2015 onwards. Photos for batches before 2015 will not be displayed.

---

## How It Works

1. **Input Validation**: Ensures the user enters a valid roll number or prefix  
2. **Image URL Generation**: Creates URLs dynamically based on the roll number pattern  
3. **Image Checking**: Validates if the image exists before rendering it  
4. **Skeleton Loader**: Shows a loading animation while images are fetched  
5. **Pagination**: Limits the number of displayed images to 100 per page and provides page navigation  
6. **LE Conversion**: Converts regular student prefixes to Lateral Entry (LE) prefixes to include LE students  

---

## Future Improvements

- Add a **search filter** for branch or year  
- Add **lazy loading** to optimize large batch image rendering  
- Implement **error fallback images** for missing student photos  
- Enhance **UI/UX** with modern card designs or animations  
- Store **recent searches** for quick access  

---

## License

This project is for educational purposes and can be freely used or modified.
