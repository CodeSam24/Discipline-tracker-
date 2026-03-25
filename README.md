# Discipline-tracker-
This is a website with form code, css and tables 

<!DOCTYPE html>

<html lang="en">

  <head>

    <title>Disipline tracker</title>

     <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

  </head>

  <body>

  <form>

  <table>

    <caption>Disipline tracker</caption>

<thead>

   <tr>

     <th>Task</th>

     <th>Target</th>

     <th>Completed</th>

   </tr>

   <tbody>

     <tr>

       <td>Workout</td>

       <td>Full session</td>

       <td><input type="checkbox"></td>

     </tr>

    

   <tr>

     <td>Coding</td>

     <td>45 min</td>

     <td><input type="checkbox"></td>

   </tr>

    

   <tr>

     <td>Reading</td>

     <td>20 min</td>

     <td><input type="checkbox"></td>

     </tr>

    </tbody>

   

    </table>

   

    <br>

   

    Rate your day:

    <input type="number" min="1" max="10"

   

       <br><br>

   

    <button type="submit">submit</button>

   

    </form>

   

  </body>

 

  </html>



table {

  border-collapse: collaspe;

  width: 100%;

}

 

th, td{

  border: 1px solid black;

  paddiiing: 8px;

  text-align: center;

}

 
