# Create A Card Component

Download the html file and open in browser to to see demoResults.

<a href='https://drive.google.com/file/d/16vw2usDBeipWyNMhRs8IAKxv_dh2pKFW/view'>DEMO PREVIEW </a>

Below is the prompt and then following are the replies given.

## Prompt

I want you to act as a Typescript Programmer who is using NextJS13 framework with tailwind css for styling. Create a reusable card component to display bookname, author, stock, quantity, type , image and price.

<ol>
  <li>We will use Typescript, with flexbox to create the component and it will be named `BooksResponsiveCard.tsx`.</li>
  <li>All cards shall maintain the same height on different screens. For it, you can wrap the stock, quantity, type, and price in a separate div at the bottom with the `mt-auto` property.</li>
  <li>Add subtle Tailwind animations for interactivity.</li>
  <li>Use React icons if needed.</li>
  <li>The data will be given in JSON format.</li>
  <li>Show a red badge "out of stock" on the top right corner of the card.  </li>
  <li>If out of stock, the buy now button should have a dim color and be unresponsive.</li>
</ol>

<p> The goal is to create an interactive books page focusing on a great eCommerce store user experience. Ask any questions if you have before creating the code</p>

<hr>

<ol>
  <li>It will be in a rectangle shape and use only NextJS 13 components</li>
  <li>The image will be on the top and rendered be NextJS Image component. Below it will be title and author before the next div that wraps other components.</li>
  <li>They will be aligned vertically. The title will be bold and black while the author will have a gray color.</li>
  <li>We will use React icons for stock, quantity, type, and price. They will be wrapped in a separate div and maintain the same width and height.</li>
  <li>It will have a linear background similar to the sold color with a yellow background. Also, add a slight shadow.</li>
  <li>We will add different subtle animations from Tailwind to enhance the card and its components' experience.</li>
  <li>The data format will be as follows: 
    <ul>
      <li>"id": 1</li>
      <li>"name": "The Russian"</li>
      <li>"author": "James Patterson and James O. Born"</li>
      <li>"isbn": "1780899475"</li>
      <li>"type": "fiction"</li>
      <li>"price": 12.98</li>
      <li>"current-stock": 12</li>
      <li>"available": true</li>
      <li>image: 'mouse.png'</li>
    </ul>
  </li>
</ol>

<hr>

<p>Show how to use this component in my page using grid system. Also add overall design and interactivity to the page.</p>
