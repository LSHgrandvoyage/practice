<!DOCTYPE html>
<head>
  <title>Lee's Post Board</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .container {
      width: 60%;
      margin: 0 auto;
    }
    h1, h2 {
      text-align: center;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      margin-bottom: 10px;
    }
    li a {
      text-decoration: none;
      color: #333;
    }
    li a:hover {
      color: #666;
    }
    form {
      margin-top: 20px;
    }
    label {
      display: block;
      margin-bottom: 5px;
    }
    input[type="text"], textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }
    botton {
      padding: 10px 20px;
      background-color: #007bff;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Post Board</h1>
    <h2> Post List </h2>
    <ul>
      <li><a href="#"> 1st Post </a></li>
      <li><a href="#"> 2nd Post </a></li>
      <li><a href="#"> 3rd Post </a></li>
    </ul>
    <h2> Write new post </h2>
    <form>
      <div>
        <label for = "title"> title: </label>
        <input type = "text" id = "title" name = "title" required>
      </div>
      <div>
        <label for = "content"> content: </label>
        <textarea id = "content" name = "content" rows = "4" required></textarea>
      </div>
      <button type = "submit"> Complete </button>
    </form>
</body>
</html>
