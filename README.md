# Book store & Shopping Cart
A responsive web application designed with HTML and Tailwind Css

## Links & Deployment
* **Task assignment:** https://www.freecodecamp.org/learn/front-end-development-libraries-v9/lab-music-shopping-cart-page/lab-music-shopping-cart-page
* **Deploy:** https://missdatauz.github.io/shopping-card-project/
* **Pull request:** https://github.com/missdatauz/shopping-card-project/pull/1

## Project overview & Description
This is a clean and responsive product card project built purely with HTML and Tailwind Css. The primary goal of this project to practice utility-first styling with Tailwind Css and build a fully responsive UI layout without writing custom CSS files.
### Key Features:
* **Tailwind CSS Utility Classes:** Clean styling implemented directly within markup using Tailwind's layout and spacing utilities.
* **Responsive Layout:** Optimized for base/mobile screens by default and desktop screens using the `lg:` breakpoint (`lg:grid`, `lg:flex`, etc.).
* **Semantic HTML5:** Built with clean, accessible HTML structure for better document flow and standard compliance.

## Tech Choice & Approach:
* **HTML5:** Semantic layout using structural elements.
* **Tailwind CSS:** Used utility classes for layout (Flexbox/Grid), custom colors, padding/margin, and responsive break-points (`lg:`).

## Local Setup & Run
To run this project locally, follow these steps:

1. **Clone the repository:**
 ```bash 
git clone https://github.com/missdatauz/shopping-card-project.git
```
2. **Navigate to the project directory:**
 ```bash
cd shopping-card-project
```

4. **Install dependencies:**
```bash
npm install
```

5. **Run Tailwind CSS watch mode:**
 ```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

6. **Open the project:**
Open index.html in your browser or use the VS Code Live Server extension.

## User Stories
<details>
  <summary><b>Click to view  all User Stories and requirements</b></summary>
  <br>
  <li>✅You should have an element with an id called shopping-cart-container.</li>
<li>✅Your #shopping-cart-container element should use the correct utility class for setting the element to a Flexbox layout.</li>
<li>✅Your #shopping-cart-container element should set the direction of flex items to column for smaller devices and row for larger devices. Remember that Tailwind CSS utilizes the mobile first approach and you will use the lg: breakpoint prefix to target larger devices.</li>
<li>✅Inside your #shopping-cart-container element, you should have an element with an id called products-container.</li>
<li>✅Your #products-container element should have at least two child elements each with a class called card.</li>
<li>✅Each .card element should have the following elements nested inside:
<li>1. An h2 element with text representing the product name, and a utility class that sets the font size using only predefined size classes such as text-sm, text-md, text-lg, text-xl, text-2xl, etc.</li>
<li>2. An element with a class called quantity and text for the number of cart items for that product.</li>
<li>3. An element with a class called price and text for the price.</li>
<li>4. A button with a class called remove-button and text Remove. Your button should have utility classes for a predefined red background color of your choosing and different predefined red background color for the hover state. Examples of predefined red background colors include bg-red-500, bg-red-600, etc. Examples of predefined hover red background colors include hover:bg-red-500, hover:bg-red-600, etc.</li>
<li>✅Inside your #shopping-cart-container element, you should have an element with an id called order-summary-container.</li>
<li>Your #order-summary-container element should have the following styles:</li>
<li>1. A utility class of your choosing for predefined rounded corners. Examples include rounded, rounded-lg, rounded-full, etc.</li>
<li>2. A utility class of your choosing for setting the border width on all sides.</li>
<li>✅Your #order-summary-container element should have the following elements nested inside:</li>
<li>1. An h2 element with the text Order Summary and a utility class of your choosing that sets the font size.</li>
<li>2. An element with the text Total: and id set to total. This element should also use utility classes to set the font weight to a predefined Tailwind CSS font weight and font size of your choosing for the element.</li>
<li>3. An element with an id set to total-amount to display the total for all items in the cart.</li>
<li>4. A link with the text Checkout and the correct utility class for centering the text. The href value should be set to #. Your link should also have a utility class for setting the background color to a predefined Tailwind CSS blue color of your choosing and a different blue background color for the hover state.</li>
</details>


## Project preview
<table align="center">
  <tr>
    <td align="center" valign="top" width="65%">
    <h4>Desktop Version<h4>
    <img width="100%" height="768" alt="image" src="https://github.com/user-attachments/assets/a4edeec9-ee94-4e49-ada6-d35fee483dde" />
    <img width="100%" height="768" alt="image" src="https://github.com/user-attachments/assets/4e5b1f41-e5c6-4adc-9ad7-c91be1d7f408" />
    </td>
      <td align="center" valign="top" width="35%">
       <h4>Mobile Version</h4> 
        <img width="100%" height="1334" alt="127 0 0 1_5501_src_index html(iPhone SE) (2)" src="https://github.com/user-attachments/assets/89a0bc4a-67c4-46a1-9fb2-b708b95c53cf" />
        <img width="100%" height="1334" alt="127 0 0 1_5501_src_index html(iPhone SE) (3)" src="https://github.com/user-attachments/assets/a07386b7-2b21-4b44-a6e2-16bd847b0582" />
      </td>
  </tr>
</table>









