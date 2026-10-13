Rwanda Nziza — Plain CSS vs Tailwind CSS

About the Project

Rwanda Nziza is a landing page that showcases the beauty, destinations, and culture of Rwanda.

This project contains two versions of the same landing page:

Plain CSS version: Uses HTML and a separate CSS stylesheet.

Tailwind CSS version: Uses Tailwind utility classes directly in HTML.

Technologies Used

HTML5

CSS3

Tailwind CSS v4

Git and GitHub

Project Structure

plain-css/ — Original landing page built with plain CSS.

tailwind/ — Landing page rebuilt using Tailwind CSS.

images/ — Images used by both versions.

Running the Project

Plain CSS Version

Open plain-css/index.html in your browser.

Tailwind CSS Version

Install the dependencies:

npm install

Build the Tailwind stylesheet:

npx @tailwindcss/cli -i ./tailwind/src/input.css -o ./tailwind/output.css

Then open tailwind/index.html in your browser.

Workflow Reflection

Rebuilding my landing page with Tailwind CSS changed how I approach styling. With plain CSS, I wrote styles in a separate stylesheet and assigned classes to HTML elements. With Tailwind, I used utility classes directly in the HTML to control spacing, colors, layout, and responsiveness.

Tailwind made styling faster because I did not need to write as many separate CSS rules or switch between files as often. However, the HTML became longer because elements needed several utility classes. This exercise helped me understand how Tailwind CSS simplifies styling and supports responsive design.