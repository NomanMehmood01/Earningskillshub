<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My first page</title>
</head>
<body>
  <Pre>
        <li>Reading</li>
        <ul>
          <li>Novels</li>
          <li>Magazines</li>
          <li>Comics</li>
        </ul>
        <ol>
          <li>Hi</li>
          <li>Bye</li>
        </ol>
      </ul>
      <table>
        <tr>
          <th>Name</th>
          <th>Roll No</th>
        </tr>
        <tr>
          <td>Noman</td>
          <td>2023-ag-7868</td>
      </table>
      <form action="submit.php" method="post">
<label for="name">Name:</label>
<input type="text" id="name" name="name">
<label for="email">Email:</label>
<input type="email" id="email" name="email">
<input type="submit" value="Submit">
<label>
<radio>
<input type="radio" value name="Class" id ="1"> Class 1 to 6
<input type="radio" value name= "Class" id="2" > Class 7 tp 10
<input type="radio" value name= "Class" id="3"> Class 11 to 14
</label>

<div>
<h4><label for="story">Tell us your story:</label>
<div>
<label for="subject">Subject:</label>
<input type="text" id="subject" name="subject">
<div>
<input type="submit" value="Submit">

<textarea id="story" name="story" rows="5" cols="33">
</textarea>
<div>
<label for="country">Country:</label>
<select id="country" name="country">
<option value="Pakistan">Pakistan</option>
<option value="USA">USA</option>
<option value="UK">UK</option>
<option value="UAE">UAE</option>
<option value="KSA">KSA</option>
<option value="Canada">Canada</option>
</select>
</div>
        <div>
<label for="file">Upload a file:</label>
<input type="file" id="file" name="file">
<input type="submit" value="Submit">
 </form>
 <div>
<input date="2023-12-31" type="date" id="start" name="trip-start">
<input type="submit" value="Submit">
 </div>
    </main>
</footer>
 </body>
</html>
