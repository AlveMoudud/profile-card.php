Assignment for ostad
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Profile Card</title>
<style>
  body, html {
    height: 100%;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #f7f7f7; /* You can also use a background image here */
  }

  .profile-card {
    width: 300px;
    padding: 20px;
    box-sizing: border-box;
    background: #ffffff; /* Background color for the card */
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    font-family: 'Arial', sans-serif;
  }

  .name {
    margin: 0;
    padding-top: 15px;
    color: #333333;
    font-size: 22px;
    font-weight: bold;
  }

  .occupation {
    color: #666666;
    font-size: 18px;
  }

  .description {
    padding: 15px 0;
    line-height: 1.5;
    color: #777777;
    font-size: 16px;
  }

  .contact-info {
    color: #888888;
    font-size: 14px;
  }
</style>
</head>
<body>

<div class="profile-card">
  <p class="name">John Doe</p>
  <p class="occupation">Web Developer</p>
  <p class="description">I'm a passionate web developer with a love for creating beautiful and functional websites.</p>
  <p class="contact-info">
    Email: john.doe@example.com<br>
    Mobile: +1234567890
  </p>
</div>

</body>
</html>
<?php
$num1 = 4;
$num2 = 5;
$num3 = 6;

if ($num1 >= $num2 && $num1 >= $num3) {
  echo "The largest number is " . $num1;
} elseif ($num2 >= $num1 && $num2 >= $num3) {
  echo "The largest number is " . $num2;
} else {
  echo "The largest number is " . $num3;
}
?>

<?php
$celsius = 32;
$fahrenheit = ($celsius * 9/5) + 32;
printf("The temperature in Fahrenheit is %.2f", $fahrenheit);
?>
