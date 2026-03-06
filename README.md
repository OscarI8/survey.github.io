
[index (2).html](https://github.com/user-attachments/files/25802772/index.2.html)
<!DOCTYPE html>
<html lang="en">

 <!--update-->

<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Movies Survey Form</title>
</head>

<body>
 <h1>Movie Survey Form</h1>
 <p>We would like to have your opinion about movies and your preferences.</p>
 <form> 
 <fieldset>
  <label for="full-name">Full Name:</label>
   <input id="full-name" type="text" name="full-name" required>
  <label for="email">Email:</label>
   <input id="email" type="email" name="email" required>
  <label for="age">Age</label>
   <input id="age" type="number" name="age" min="13" max="120" required>
 </fieldset>

 <h2>Movie Genre</h2>
 <fieldset>
  <legend>What type of movies do you like to watch?</legend>
  
  <label for="action">Action</label>
   <input id="action" type="checkbox" name="action">
  <label for="horror">Horror</label>
   <input id="horror" type="checkbox" name="horror">
  <label for="comedy">Comedy</label>
   <input id="comedy" type="checkbox" name="comedy">
  <label for="drama">Drama</label>
   <input id="drama" type="checkbox" name="drama">
  <label for="sci-fi">Sci-fi</label>
   <input id="sci-fi" type="checkbox" name="sci-fi">
  <label for="other-genre">Other</label>
   <input id="other-genre" type="checkbox" name="other">
 </fieldset>

 <h2>Your Setting to Watch a Movie</h2>
 <h3>Time</h3>
 <fieldset>
  <legend>What's your favourite time to watch a movie?</legend>

  <label for="dropdown">Time</label>
   <select id="dropdown" name="time">
    <option value="morning">Morning</option>
    <option value="afternoon">Afternoon</option>
    <option value="night">Night</option>
   </select>
 </fieldset>

  <h3>Your Favourite Place</h3>
 <fieldset>
  <legend>What's your favorite place to watch a movie?</legend>

  <label for="cinema">Cinema</label>
   <input id="cinema" type="radio" name="place" value="cinema">
  <label for="room">Room</label>
   <input id="room" type="radio" name="place" value="room">
  <label for="living-room">Living Room</label>
   <input id="living-room" type="radio" name="place" value="living-room">
  <label for="other-place">Other</label>
   <input id="other-place" type="radio" name="place" value="other-place">
 </fieldset>

 <h3>One More Question...</h3>
 <fieldset>
  <legend>How often do you watch movies?</legend>

  <label for="everyday">Everyday</label>
   <input id="everyday" type="radio" name="frequency" value="everyday">
  <label for="once-a-week">Once a Week</label>
   <input id="once-a-week" type="radio" name="frequency" value="once-a-week">
  <label for="more-than-2-times-a-week">More than 2 Times a Week</label>
   <input id="more-than-2-times-a-week" type="radio" name="frequency" value="more-than-2-times-a-week">
  <label for="only-on-the-weekends">Only on the Weekends</label>
   <input id="only-on-the-weekends" type="radio" name="frequency" value="only-on-the-weekends">
 </fieldset>

 <h2>Comments</h2>
 <fieldset>
  <legend>Any Comments...</legend>
  <label for="comments">Comments</label>
   <textarea name="comments" id="comments" placeholder="leave comments here..."></textarea>
 </fieldset>
 <button type="submit">Submit</button>
 </form>
 <footer>
  <h2>About</h2>
  <p>Name: Oscar Pichardo</p>
  <p>Email:<a href="mailto:oscarp1810@gmail.com">oscarp1810@gmail.com</a></p>
 </footer>
</body>
</html>
  





