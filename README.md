Live Demo:
[https://your-frontend-url.con](https://squidgame-beryl.vercel.app/)

# 🦑 Squid Game Landing Page

A frontend landing page inspired by the **Squid Game** series, built using **HTML5**, **SCSS**, **CSS Flexbox**, and **CSS Positioning**.

This project was created as part of a frontend assignment where the goal was to recreate the given UI as closely as possible while improving layout-building and CSS skills.

---

# 📌 Assignment Objective

The objective of this assignment was to recreate the given design using:

- CSS Flexbox
- `position: relative`
- `position: absolute`

Along with building the UI, the assignment also focused on improving research skills, problem-solving ability, and understanding real-world frontend layouts.

---

# 🚀 Technologies Used

- HTML5
- SCSS
- CSS3
- CSS Flexbox
- CSS Position (Relative & Absolute)
- Remix Icons

---

# 📚 What I Learned

While working on this project, I learned how to convert a UI design into code step by step instead of writing CSS randomly.

Some important things I learned are:

- Creating layouts using Flexbox
- Using Relative and Absolute Positioning
- Layering elements properly
- Organizing styles using SCSS
- Creating reusable mixins
- Breaking a complex UI into smaller sections
- Maintaining proper spacing and alignment
- Improving debugging and research skills

---

# 🎨 SCSS Usage

Instead of writing everything in one CSS file, I used **SCSS** to keep the project clean and organized.

I divided the styles into reusable files like:

```text
SCSS
│
├── base
│   ├── _reset.scss
│   └── _typography.scss
│
├── abstracts
│   ├── _variables.scss
│   └── _mixins.scss
│
└── style.scss
```

I also created reusable mixins such as:

- `flex()`
- `dimensions()`
- `circle()`
- `custom-absolute()`
- `bg-image()`

Using mixins reduced repetitive CSS and made the project much easier to maintain.

---

# 🛠️ Design Process

Before writing CSS, I first analyzed the reference design and divided it into smaller sections.

```text
Hero Section
│
├── Navbar
├── Left Content
├── Center Character
├── Right Information Cards
└── Footer
```

After completing the HTML structure, I styled one section at a time. This made debugging easier and helped me keep the code organized.

---

# 🔍 Research Process

Before asking for help, I followed this process:

1. Tried solving the issue on my own.
2. Searched for solutions on Google.
3. Used ChatGPT to understand difficult CSS concepts.
4. Collected images and assets from Google and free PNG websites.
5. Compared my UI with the reference design and kept improving it.

This process improved both my research and debugging skills.

---

# 💡 Challenges Faced

### Hero Section

Positioning the center character image while keeping the left and right sections properly aligned was the biggest challenge.

I solved this using:

- `position: relative`
- `position: absolute`
- `transform: translate()`

---

### Footer Product Cards

Initially, the product cards were not aligned properly.

Problems I faced:

- Images were overflowing
- Text alignment looked incorrect
- Spacing between cards was uneven

I solved these issues by adjusting Flexbox alignment, image container size, padding, gap, and flex values.

---

### Right Information Section

Creating the connector line and decorative dots between the icons was another challenge.

For this, I learned how to use:

- `::before`
- `::after`

without adding extra HTML elements.

---

### Finding Assets

The original design assets were not provided.

I searched for:

- Background images
- Character images
- Product images
- Icons
- Logos

using Google Search and free PNG websites.

---

# ✨ Features

- Full-screen landing page
- Navigation bar
- Hero section
- Center character image
- Right-side information cards
- Footer product cards
- Gradient buttons
- Flexbox-based layout
- CSS Positioning
- Organized SCSS structure
- Reusable SCSS mixins

---

# 📈 Skills Improved

This assignment helped me improve my:

- HTML structuring
- CSS Flexbox
- CSS Positioning
- SCSS architecture
- UI understanding
- Research skills
- Problem-solving
- Debugging
- Code organization
- Writing reusable styles

---

# 🚀 Future Improvements

In future versions, I would like to add:

- Responsive design
- CSS animations
- Hover effects
- Better typography
- Accessibility improvements
- Interactive UI elements
- Smooth transitions

---

# 📖 Conclusion

This project helped me understand that building a UI is not just about writing CSS.

I learned how to analyze a design, divide it into smaller sections, decide where to use Flexbox and Positioning, organize styles using SCSS, and write reusable code.

The biggest learning from this assignment was improving my frontend thinking process. Instead of directly writing CSS, I now first plan the layout, build the HTML structure, and then style each section step by step.

Overall, this assignment strengthened my understanding of HTML, CSS Flexbox, CSS Positioning, SCSS, and real-world frontend development.
