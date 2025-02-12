body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1rem;
    text-align: center;
}

h1 {
    margin: 0;
}

button {
    background-color: #008CBA;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

button:hover {
    background-color: #005f6a;
}

#boards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 1rem;
}

.board {
    background-color: white;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 0.5rem;
    padding: 1rem;
    width: 200px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.board img {
    max-width: 100%;
    height: auto;
    display: block;
    margin-bottom: 0.5rem;
}

.board button {
    background-color: #f44336;
}

.board button:hover {
    background-color: #c23621;
}
