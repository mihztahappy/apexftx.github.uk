<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="main.css">
    <img src="https://www.cs.umd.edu/sites/default/files/styles/medium/public/images/partners/Vidoori%20Logo%20Vector%20Transparent-%20A.png?itok=i9TS3xiM" alt="Picture of me" width= "85" height= "32">
                                                                                           
    <body>
      <h1>Employee Telework Request</h1>
  </body>
    <form>
            Day Requested
            <input type="date" name="day">
          </form>
          <br>
          <form>
            Starting Time 
            <input type="time" name="usr_time">
          </form>
          <form>
            Finishing Time
            <input type="time" name="usr_time">
          </form> 
          <br>
          <form>
            Break Starting Time (optional)
            <input type="time" name="usr_time">
          </form>
          <form>
            Break Ending Time (optional)
            <input type="time" name="usr_time">
          </form>
          <br>

          <form>
            <input type="number" name="quantity" min="1" max="24">
            <input type="submit"> 
          </form>
            
    <form>
            Total Number of Hours Planning on Working (based on times entered above)
            <input type="number" name="quantity" min="1" max="24">
            <input type="submit"> 
          </form>
</head>
</html>
