# survey-form

<!DOCTYPE html>
<html>
<head>
  <title>Survey Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 600px;
      margin: 20px auto;
      padding: 20px;
      background-color: #f5f5f5;
    }

    h1 {
      text-align: center;
    }

    form {
      margin-top: 20px;
    }

    label {
      display: block;
      margin-bottom: 10px;
    }

    input[type="text"],
    textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
    }

    input[type="radio"],
    input[type="checkbox"] {
      margin-right: 5px;
    }

    button {
      display: block;
      width: 100%;
      padding: 10px;
      background-color: #333333;
      color: #ffffff;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: #555555;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Survey Form</h1>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required>

      <label for="age">Age:</label>
      <input type="number" id="age" name="age" min="18" max="100" placeholder="Enter your age" required>

      <label for="gender">Gender:</label>
      <input type="radio" id="male" name="gender" value="male" required>
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="female" required>
      <label for="female">Female</label>
      <input type="radio" id="other" name="gender" value="other" required>
      <label for="other">Other</label>

      <label for="feedback">Feedback:</label>
      <textarea id="feedback" name="feedback" placeholder="Enter your feedback" required></textarea>

      <label for="agree">I agree to the terms and conditions:</label>
      <input type="checkbox" id="agree" name="agree" required>

      <button type="submit">Submit</button>
    </form>
  </div>
</body>
</html>
