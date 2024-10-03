# custom-star-rating

custom-star-rating
A customizable React component for adding star ratings to your application, with flexible properties for rating count, size, color, and optional message displays.

# Installation

You can install the package via npm:

npm install custom-star-rating

Or with Yarn:

yarn add custom-star-rating

# Publish by

```js
Aman Poddar
E-mail- amanpoddar775@gmail.com
```

# Usage

Here's an example of how to use the StarRating component in a React project:

```js
import React from "react";
import StarRating from "custom-star-rating"; // Import the package

function App() {
  return (
    <div>
      <h1>Movie Rating</h1>
      <StarRating
        maxRating={5}
        defaultRating={3}
        size={40}
        color="gold"
        onSetMovieRating={(rating) => console.log(`New rating: ${rating}`)}
        messages={["Bad", "Okay", "Good", "Great", "Excellent"]}
      />
    </div>
  );
}

export default App;
```

# Props

Prop Name Type Description Default Value
maxRating number Maximum number of stars 5
defaultRating number Initial rating value 0
size number Size of each star (in pixels) 49
color string Color of the stars (any valid CSS color) #FFFF00
messages array Optional array of messages for each rating []
onSetMovieRating function Callback function that returns the selected rating value undefined
count boolean Whether to show the rating count or message alongside the stars true

# Features

Fully customizable star rating.
Changeable number of stars (maxRating).
Dynamic sizing and color for stars.
Optionally displays messages associated with each rating.
Handles mouse hover states for rating previews.
Works with any React project.

# Example

```js
git clone https://github.com/amanpoddar-dev12/custom-star-rating
cd custom-star-rating
npm install
npm start
```

you can test the star rating component by changing props and observing the changes dynamically.

# License

This project is licensed under the ISC License. See the LICENSE file for details.

# Version History

1.0.0
Initial release with basic star rating functionality.
