# Quick URL Preview Application

## Description
The Quick URL Preview Application is a web-based tool that allows users to save, view, and manage website links. Users can add site names and URLs, preview saved links, and delete them when no longer needed. This application offers a clean, user-friendly interface for organizing links efficiently.

## Features
- Add website links by specifying a site name and URL.
- View saved links with their respective names.
- Delete links with a single click.
- Minimalistic and visually appealing UI.
- Built with responsive design for seamless usage across devices.
- Local storage support for persisting links across sessions.
- Intuitive error handling for invalid or duplicate URLs.
- Option to copy saved URLs to the clipboard.
- Categorization of links for better organization.
- Dark mode support for comfortable usage at night.

## Design
### Color Palette
- **Background:** Gradient from light green to soft yellow.
- **Card Background:** Soft beige with slight shadow for depth.
- **Button Colors:** 
  - **Add URL:** Vibrant green for positive actions.
  - **Delete Icon:** Red for destructive actions.

### Fonts
- **Primary Font:** Sans-serif, elegant and readable.
- **Headings:** Bold with slightly larger font sizes for better visual hierarchy.

### Layout
- Centralized form with evenly spaced input fields and buttons.
- Links displayed as responsive cards with hover effects.
- Mobile-friendly design with adaptive grid for link cards.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Framework:** React.js
- **Styling:** Tailwind CSS
- **Storage:** LocalStorage (for persisting data)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quick-url-preview.git
   ```

2. Navigate to the project directory:
   ```bash
   cd quick-url-preview
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open the application in your browser at:
   ```
   http://localhost:3000
   ```

## Usage
1. Enter a site name and URL in the input fields.
2. Click the **Add URL** button to save the link.
3. View all saved links displayed as cards below the input fields.
4. Use the delete button (red trash icon) to remove unwanted links.
5. Click on the copy icon to copy the URL to the clipboard.
6. Use the categories dropdown to filter and organize your links.

## Screenshots
![Quick URL Application](./screenshot.png)

## Future Enhancements
- Add validation for URLs.
- Enable editing of saved links.
- Implement a search feature for quick access to specific links.
- Provide cloud storage for persistent data management.
- Add a feature to export and import links as a JSON file.
- Integrate user authentication for personalized link management.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any inquiries or support, feel free to reach out:
- **Email:** your-email@example.com
- **GitHub:** [your-username](https://github.com/your-username)

---

Enjoy organizing your links with the Quick URL Preview Application!
