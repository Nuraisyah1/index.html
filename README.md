<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu Planner</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Weekly Menu Planner</h1>
    <nav>
      <ul>
        <li><a href="#monday">Monday</a></li>
        <li><a href="#tuesday">Tuesday</a></li>
        <li><a href="#wednesday">Wednesday</a></li>
        <li><a href="#thursday">Thursday</a></li>
        <li><a href="#friday">Friday</a></li>
        <li><a href="#saturday">Saturday</a></li>
        <li><a href="#sunday">Sunday</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Overview</h2>
      <p>Plan your weekly meals easily with images, nutritional data, and recipe links.</p>
      <figure>
        <img src="https://via.placeholder.com/300x200" alt="Meal planning image">
        <figcaption>Stay organized and eat better.</figcaption>
      </figure>
    </section>

    <section id="monday">
      <h2>Monday</h2>
      <article>
        <h3>Breakfast</h3>
        <ul>
          <li>Oatmeal with banana <a href="#">(Recipe)</a></li>
        </ul>
        <h3>Lunch</h3>
        <ul>
          <li>Grilled chicken salad <a href="#">(Recipe)</a></li>
        </ul>
        <h3>Dinner</h3>
        <ul>
          <li>Spaghetti with marinara sauce <a href="#">(Recipe)</a></li>
        </ul>
      </article>
    </section>

    <section id="tuesday">
      <h2>Tuesday</h2>
      <article>
        <h3>Breakfast</h3>
        <ul>
          <li>Scrambled eggs and toast <a href="#">(Recipe)</a></li>
        </ul>
        <h3>Lunch</h3>
        <ul>
          <li>Turkey sandwich <a href="#">(Recipe)</a></li>
        </ul>
        <h3>Dinner</h3>
        <ul>
          <li>Stir-fried vegetables with rice <a href="#">(Recipe)</a></li>
        </ul>
      </article>
    </section>

    <!-- Continue similarly for the rest of the week -->

    <section id="feedback">
      <h2>Feedback</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br>
        <label for="comments">Comments:</label><br>
        <textarea id="comments" name="comments" rows="4" cols="50"></textarea><br>
        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Menu Planner. All rights reserved.</p>
  </footer>
</body>
</html>
