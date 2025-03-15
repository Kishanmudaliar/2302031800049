* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header {
    background-color: #0a3d62;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 40px;
    text-align: center;
}

.subscribe button, #contact button, #sign-up button {
    background-color: #e67e22;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

.subscribe button:hover, #contact button:hover, #sign-up button:hover {
    background-color: #d35400;
}

form {
    display: flex;
    flex-direction: column;
    gap: 10px;
    width: 300px;
    margin: auto;
}

form input, form textarea {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

footer {
    background-color: #0a3d62;
    color: white;
    text-align: center;
    padding: 20px;
}
