 BST Visualizer

BST Visualizer is a web-based application that allows users to understand how a **Binary Search Tree (BST)** works by showing a real-time visual representation when values are inserted into the tree. This project is designed to help students and beginners easily learn and visualize BST concepts.

The application is built using **HTML, CSS, and JavaScript** and is deployed using **Docker** with an automated **Jenkins CI/CD pipeline**.

🔗 **Live Demo:** https://bstvisual.netlify.app/  
🔗 **GitHub Repository:** https://github.com/srinivasa29/bst-visulaizer  

---

 Features

- Insert numbers into a Binary Search Tree  
- Visual display of the BST structure  
- Real-time node placement  
- Simple and clean user interface  
- Works directly in the browser  

---
 Technologies Used

- **HTML** – Structure of the web pages  
- **CSS** – Styling and layout  
- **JavaScript** – Logic for BST operations and visualization  
- **Docker** – Containerization of the application  
- **Jenkins** – CI/CD pipeline for automated build and deployment  

---
How the Application Works

1. The user enters a number in the input field.  
2. JavaScript inserts the value into the Binary Search Tree.  
3. The BST follows its rules:
   - Left child nodes contain smaller values  
   - Right child nodes contain larger values  
4. The updated tree is displayed visually on the screen.  

This makes it easier to understand how BST insertion works step by step.

---

 How to Run the Project Locally

1. Clone the repository:
git clone https://github.com/srinivasa29/bst-visulaizer.git

cd bst-visulaizer

2. Open the `index.html` file in any web browser.

 Run Using Docker

1. Build the Docker image:
   docker build -t bst-visualizer .
   
2. Run the container:

docker run -p 8080:80 bst-visualizer


3. Open in browser:



http://localhost:8080


 Jenkins CI/CD Pipeline

This project uses **Jenkins** to automate the deployment process.  
Whenever new code is pushed to GitHub, Jenkins:

- Pulls the latest code  
- Builds the Docker image  
- Runs the container automatically  

This ensures the application is always deployed with the latest updates.

---

 Use Cases

This project is helpful for:
- Students learning Data Structures  
- Visualizing Binary Search Tree operations  
- Understanding how BSTs are built  

---

 Author

**Seenu (Mannepula Srinivasa)**  
B.Tech Computer Science Student  

GitHub: https://github.com/srinivasa29



