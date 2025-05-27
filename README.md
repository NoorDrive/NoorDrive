body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #fff;
    color: #333;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #001524;
    color: white;
    padding: 1rem 2rem;
}

.logo {
    display: flex;
    align-items: center;
}

.logo img {
    height: 50px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 2rem;
    text-align: center;
}

.cars {
    display: flex;
    justify-content: center;
    gap: 2rem;
    flex-wrap: wrap;
}

.car {
    border: 1px solid #ccc;
    padding: 1rem;
    width: 250px;
    border-radius: 8px;
}

.car img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

button {
    background-color: #c79a33;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
    margin-top: 10px;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: 0 auto;
    gap: 1rem;
}

form input, form textarea {
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #001524;
    color: white;
}
