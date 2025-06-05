body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f4f4f4;
}

header {
  background-color: #004080;
  color: white;
  padding: 20px;
  text-align: center;
}

.container {
  max-width: 800px;
  margin: 20px auto;
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

h2 {
  color: #004080;
  margin-bottom: 20px;
}

label {
  display: block;
  margin-top: 15px;
}

input, select, textarea {
  width: 100%;
  padding: 10px;
  margin-top: 5px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

button {
  margin-top: 20px;
  background-color: #004080;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background-color: #003060;
}

@media (max-width: 600px) {
  .container {
    margin: 10px;
    padding: 15px;
  }

  button {
    width: 100%;
  }
}
