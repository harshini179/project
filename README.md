File Upload Manager
A modern File Upload Manager web application built using HTML, CSS, and JavaScript. This project allows users to select multiple files, preview them with size details, and simulate file uploads with progress bars.

Features
Select multiple files at once.
Preview selected files with name and size.
Simulated upload with animated progress bars.
Modern, responsive UI with hover effects.
Ready to integrate with backend for real uploads.

Technologies Used
HTML5 – Structure and file input.
CSS3 – Styling, responsive layout, hover effects.
JavaScript (ES6) – File handling, progress bar simulation.

How to Use

Clone the repository
git clone https://github.com/harshini179/project.git
cd project

2. Open the HTML file

Open index.html in any modern browser (Chrome, Firefox, Edge).

3. Select and Upload Files

Click Choose Files to select files.

Click Upload Files to see the progress animation.


Future Enhancements

Integrate real backend upload using Node.js/Express.

Display individual progress for each file during real upload.

Add file type restrictions and validation.

Enable remove file option before upload.

Implement drag-and-drop file upload.



Project Report

Project Title: File Upload Manager  

Objective
The objective of this project is to build a user-friendly web application that allows users to select multiple files, preview them, and simulate an upload process with progress tracking. This project demonstrates the use of HTML, CSS, and JavaScript for creating interactive and modern web interfaces.



Features
- Select and preview multiple files.
- Display file size.
- Simulated upload with progress bars.
- Responsive and modern UI.
- Easy to integrate with backend systems.



Tools and Technologies
- HTML5– For structure and input handling.
- CSS3 – For styling, layout, and animations.
- JavaScript (ES6) – For dynamic file handling and progress bar simulation.
- Optional backend integration: Node.js / Express.



System Design
1. Frontend
   - `index.html` – Main web page.
   - CSS for styling (`style` tag in head or external file).
   - JavaScript handles file selection, display, and upload simulation.

2. File Handling
   - Users select files using an `<input type="file" multiple>`.
   - Selected files are stored in a JS array.
   - File name and size are displayed in a list.
   - Progress bars simulate upload progress.



Workflow
1. User opens the application in a browser.
2. Clicks Choose Files to select multiple files.
3. Selected files are displayed with their name and size.
4. Click Upload Files to start the simulated upload.
5. Progress bars animate from 0% to 100% for each file.
6. Alert notifies completion of the upload simulation.



Challenges and Solutions
- Challenge: Display multiple files dynamically.  
  Solution: Used JavaScript `forEach` loop to create `<li>` elements dynamically.

- Challenge: Simulate upload progress.  
  Solution: Used `setInterval` to animate the progress bar incrementally.

- Challenge:Responsive layout.  
  Solution: Used flexbox and relative widths for different screen sizes.



Future Enhancements
- Integrate real backend upload with progress tracking.
- Add file type and size validation.
- Allow removing files before upload.
- Support drag-and-drop upload.
- Save uploaded files on the server.



Conclusion
The File Upload Manager provides a clean and interactive interface for file uploads. It can be enhanced to a fully functional web application by connecting it to a backend server. This project showcases skills in frontend development, dynamic DOM manipulation, and UI/UX design principles.


