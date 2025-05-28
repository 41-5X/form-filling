<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>WIPRO TECH HIRE</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: black;
      background-image: url('https://images.unsplash.com/photo-1518770660439-4636190af475'); /* example computer image */
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .form-container {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 30px;
      border-radius: 10px;
      width: 350px;
    }

    h2 {
      text-align: center;
      color: #00ffcc;
    }

    label {
      display: block;
      margin-top: 15px;
      font-size: 14px;
    }

    input, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border-radius: 5px;
      border: none;
    }

    button {
      margin-top: 20px;
      width: 100%;
      padding: 10px;
      background-color: #00ffcc;
      border: none;
      border-radius: 5px;
      color: black;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background-color: #00cca3;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h2>WIPRO TECH HIRE</h2>
    <form>
      <label for="name">Full Name:</label>
      <input type="text" id="name" required>

      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" required>

      <label for="address">Address:</label>
      <textarea id="address" rows="2" required></textarea>

      <label for="guardian">Guardian Name:</label>
      <input type="text" id="guardian" required>

      <label for="qualification">Qualification:</label>
      <input type="text" id="qualification" required>

      <button type="submit">Submit</button>
    </form>
  </div>
</body>
</html>
