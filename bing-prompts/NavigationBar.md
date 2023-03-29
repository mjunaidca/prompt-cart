# Create A Navigation Bar

This prompt creates an optimized Navigation Bar.

## Prompt

Please act as a full stack developer proficient in nextjs, tailwind css and typescript. Create a Navbar component. It will have a logo, 1 search bar, 4 pages, and a single button in the navigation bar. The logo and search bar are one group and pages and buttons will be another group and these 2 group have a little more space between them.

<ol>
  <li>We will use Typescript, with flexbox or grid and it will be named `NAVBAR.tsx`.</li>
  <li>Create a simple Hamburger menu for mobile screens and proper Navbar for desktop. Use `AiOutlineMenu`, `AiOutlineClose` from React icons and give them white color.</li>
  <li>Use NextJS13 `<Link>` and `<Image>` component. Don't use `<a>` tag with Link component.</li>
  <li>The background will be black with white text and a gray color for the placeholder.</li>
  <li>The goal is to create an interactive Navigation Bar for a Books eCommerce store. Ask any questions if you have before creating the code.</li>
</ol>

<hr>

<ol>
  <li>
    <ul>
      <li>{ name: "Home", link: "/" }</li>
      <li>{ name: "Product", link: "/product" }</li>
      <li>{ name: "About", link: "/about" }</li>
      <li>{ name: "Pricing", link: "/pricing" }</li>
    </ul>
  </li>
  <li><img src="./next.svg" alt="Book Store"></li>
  <li>Text: Buy Now, link: <a href="./buy-now">'./buy-now'</a></li>
  <li>Placeholder will take a number take to the dynamic segment <code>./book/:[bookId]</code>.</li>
  <li>Add simple effects using Tailwind CSS.</li>
</ol>

<hr>

Show how to use this component. Also add overall design and mock data.

