body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
}

header {
    background: #fff;
    padding: 10px 0;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

#intro {
    text-align: center;
    padding: 50px 20px;
}

#intro h1 {
    margin: 0;
    font-size: 2.5em;
}

#intro h2 {
    color: #888;
    margin: 10px 0;
}

.projects-row {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin: 20px 0;
}

.project {
    text-align: center;
    background: #f9f9f9;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    width: calc(50% - 20px);
    margin: 10px;
}

.project-image {
    width: 100%;
    height: 800px;
    background: #ccc;
    margin-bottom: 10px;
    border-radius: 10px;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    object-fit: contain;

}

.project-image img {
    width: 100%;
    height: auto;
    max-height: 100%;
    object-fit: cover;
}

#experience {
    padding: 20px;
}

.job {
    margin-bottom: 20px;
}

#contact {
    background: #f9f9f9;
    padding: 20px;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form label {
    margin-top: 10px;
}

form input, form textarea {
    width: 80%;
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    margin-top: 20px;
    padding: 10px 20px;
    border: none;
    background: #333;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background: #555;
}
