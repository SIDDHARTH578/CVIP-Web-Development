<!DOCTYPE html>
<html>
<head>
</head>
<body>
 <div class="main">
    <h1>Golden Task Button</h1>
    <button id="myButton">Click Me</button>
    <p id="message"></p>
  </div>
</body>
</html>

<style>
 .main {
        text-align: center;
        padding: 50px;
    }
  #myButton {
    background-color: cyan;
    color: black;
    font-weight: bold;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 8px;
  }
p{
font-size:25px;
font-weight:900;
color:red;
}
</style>

<script>
  // JavaScript code
   const button = document.getElementById('myButton');
  const message = document.getElementById('message');

  button.addEventListener('click', () => {
    message.textContent = 'Golden Task';
  });
</script>