### Project Overview: Testpoints / Pinouts Directory 📱

#### Purpose 🎯:
The project is designed to serve as a directory for "Testpoints" and "Pinouts" related to various smartphone brands.

#### Features 🛠:

1. **Display Data from Baserow Tables** 📊:
   - The main content of the webpage is a table that pulls data from Baserow, an online database service.
   - The data includes smartphone models 📱, images 🖼, and their sources 🔍 from various brands like Nokia, Huawei, Oppo, Vivo, and Samsung.
   - Each row in the table displays the model name, a clickable image (which can be enlarged), and the source of the data.

2. **Interactive Features** ⚡:
   - **Search Functionality 🔍**: Users can filter the table based on the model name.
   - **Brand Filters 🏷**: Users can also filter the data based on brands using button chips.
   - **Image Enlargement 🔍📸**: Clicking on an image brings it up in a lightbox-style enlarged view. There are also zoom-in and zoom-out options available.
   - **Night Mode Toggle 🌙/☀**: The webpage supports a dark theme, which can be toggled on and off. The initial theme matches the user's system preference.

3. **Aesthetics & UI** 🎨:
   - The design uses a clean and modern aesthetic with a specific color scheme, and the layout is responsive for mobile devices 📱🖥.
   - Custom fonts are applied for a more refined look 🖋.
   - UI elements like brand filter chips and search bars provide a user-friendly experience 👥.
   - Animated transitions, like the fade effect for night mode toggling, enhance user interaction 💫.

#### How It Works 🤖:

- **Data Loading** 🔄: 
  - The data is fetched using Baserow's API. Multiple asynchronous requests are made to gather data from various tables corresponding to different brands.
  - Once all data is loaded, it populates the table, and the total count of models is displayed.

- **Interactivity** 🎮:
  - **Filtering**: Both the search bar and brand chips use JavaScript to manipulate the DOM, hiding or displaying rows based on the user's input or selection.
  - **Image Lightbox 🖼**: Utilizes CSS for styling and JavaScript for functionality. The images can be zoomed in/out, and clicking outside the image or on the close button will close the lightbox view.
  - **Night Mode 🌓**: The theme of the website can be toggled using JavaScript by adding or removing specific classes. The initial theme is determined based on the user's system preference.

Overall, the project provides a visually appealing 🌈 and user-friendly platform for users interested in testpoints and pinouts of various smartphone models. It pulls dynamic data from Baserow, ensuring that the content can be updated easily without modifying the code. 🚀
