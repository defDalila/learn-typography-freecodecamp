# <p align="center"><font color='#FF79C6'><strong>Learn Typography by Building a Nutrition Label</strong></font></p>

<p align="center"> <i>Módulo de treinamento para a certificação <a href="https://www.freecodecamp.org/learn/2022/responsive-web-design/"><em>Responsive Web Design Certification</em></a> da plataforma FreeCodeCamp</i>.
<p>

<p align="center">
    <img src="https://skillicons.dev/icons?i=html,css,md,vscode,git,github" height="30px">
</p>


<br>

## :memo: <font color='#8BE9FD'><strong>Notas de Aula</strong></font>

<br>

## Borders

Borders in CSS are a powerful visual tool for grouping, prioritizing, and separating content within a webpage. By adding borders, you can visually organize different sections or elements, draw attention to specific areas, or simply improve the overall layout and user experience.

### Ways to Use Borders for Grouping and Prioritizing Content:

1. **Grouping Content**:  
   Borders can be used to group related content together. For instance, putting a border around a section, card, or container can indicate that the contents within are related.

   **Example:**

   ```css
   .card {
     border: 2px solid #333; /* Adds a border around the card */
     padding: 20px;
   }
   ```

2. **Prioritizing Content**:  
   You can use borders to highlight or emphasize important elements. For example, adding a thick or colored border around a featured content box can make it stand out and prioritize its visibility.

   **Example:**

   ```css
   .featured {
     border: 4px solid #ff5733; /* Highlighted border with a bold color */
     padding: 15px;
     background-color: #f9f9f9;
   }
   ```

3. **Creating Sections**:  
   Borders can help divide a page or layout into different sections. This creates a clean, organized structure, especially when content needs to be segmented.

   **Example:**

   ```css
   .section {
     border-top: 3px solid #ddd;
     border-bottom: 3px solid #ddd;
     margin: 20px 0;
     padding: 10px;
   }
   ```

4. **Hover Effects**:  
   Adding borders on hover can create interactive experiences. For example, showing a border around an element when a user hovers over it can visually indicate that the element is interactive.

   **Example:**

   ```css
   .item:hover {
     border: 2px solid #007bff; /* Adds a blue border when the item is hovered */
     cursor: pointer;
   }
   ```

5. **Decorative Borders**:  
   Borders can also be used for purely aesthetic purposes, adding visual interest to the page without necessarily altering the content's hierarchy.

   **Example:**

   ```css
   .decorative {
     border: 2px dashed #777; /* Adds a dashed border for decoration */
     padding: 15px;
   }
   ```

6. **Rounded Borders for Soft Edges**:  
   Adding a border-radius property can create soft, rounded corners that make an element appear less rigid and more inviting.

   **Example:**

   ```css
   .rounded {
     border: 2px solid #4CAF50;
     border-radius: 15px; /* Rounded corners for a softer appearance */
     padding: 20px;
   }
   ```

7. **Using Multiple Borders**:  
   You can even use multiple borders with different thicknesses and colors for emphasis or visual layering.

   **Example:**

   ```css
   .double-border {
     border: 5px solid #333;
     border-width: 5px 10px; /* Different thickness for top/bottom and left/right */
     padding: 20px;
   }
   ```

Borders can not only help structure content but can also draw attention to important elements, separate sections, or enhance the user interface design. By creatively using borders in conjunction with other CSS properties, you can improve both the functionality and aesthetics of a webpage.

## fine-tune

To fine-tune the placement of your **`h1`** element, you can adjust its margins using negative values. This will shift the element slightly in the respective directions. In this case, you want to apply a **-4px** margin to the top and bottom, and **0px** to the left and right.

Here’s the CSS rule:

```css
h1 {
  margin: -4px 0; /* -4px for top and bottom, 0px for left and right */
}
```

### Explanation:
- **`-4px`** for the **top** and **bottom**: This will shift the `h1` slightly upwards and reduce any extra space between the `h1` and the surrounding content.
- **`0px`** for the **left** and **right**: Ensures there is no additional margin on the sides, keeping it aligned as intended.

This adjustment should help in refining the position of your `h1` element for a better visual outcome!


## Lines

Lines, or borders, are effective for separating and grouping content, especially when the available space is limited. They provide clear visual cues that help users understand how information is organized on the page. Here are several ways lines can be used to enhance content layout:

### 1. **Horizontal Lines (Dividers)**:
   Horizontal lines can be used to separate sections of content, making the layout cleaner and more structured.

   **Example:**

   ```css
   .divider {
     border-top: 1px solid #ccc; /* Adds a thin gray horizontal line */
     margin: 20px 0; /* Adds spacing above and below the line */
   }
   ```

   **HTML:**

   ```html
   <div class="section">
     <p>Some content...</p>
     <div class="divider"></div> <!-- Horizontal line separating content -->
     <p>More content...</p>
   </div>
   ```

### 2. **Vertical Lines**:
   Vertical lines can be used to separate columns or different sections within the same row. These are especially useful in layouts like sidebars or multi-column designs.

   **Example:**

   ```css
   .sidebar {
     border-left: 2px solid #333; /* Adds a thick vertical line */
     padding-left: 20px;
   }
   ```

   **HTML:**

   ```html
   <div class="container">
     <div class="main-content">Main content here...</div>
     <div class="sidebar">Sidebar content...</div>
   </div>
   ```

### 3. **Dashed or Dotted Lines**:
   Dashed or dotted lines can give a softer or more playful look to the page, while still providing the same separating functionality as solid lines.

   **Example:**

   ```css
   .dashed-line {
     border-top: 2px dashed #666; /* Adds a dashed horizontal line */
     margin: 20px 0;
   }
   ```

   **HTML:**

   ```html
   <div class="content">
     <p>Some content above the dashed line</p>
     <div class="dashed-line"></div>
     <p>Some content below the dashed line</p>
   </div>
   ```

### 4. **Line with Shadows**:
   Adding a shadow effect to a line can make it appear more dynamic, adding depth to the design.

   **Example:**

   ```css
   .shadow-line {
     border-top: 2px solid #333;
     box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow under the line */
     margin: 20px 0;
   }
   ```

   **HTML:**

   ```html
   <div class="content">
     <p>Some content above the line with shadow</p>
     <div class="shadow-line"></div>
     <p>Some content below the line with shadow</p>
   </div>
   ```

### 5. **Border Radius for Rounded Lines**:
   By applying a border-radius to lines (especially in small sections), you can create softer edges, making the lines less harsh.

   **Example:**

   ```css
   .rounded-line {
     border-top: 3px solid #3498db;
     border-radius: 5px; /* Creates rounded corners */
     margin: 20px 0;
   }
   ```

   **HTML:**

   ```html
   <div class="content">
     <p>Content before the rounded line</p>
     <div class="rounded-line"></div>
     <p>Content after the rounded line</p>
   </div>
   ```

### 6. **Lines for Grouping Content**:
   Using lines to group content can help make information appear more organized. For example, a line under the title or above key sections can draw attention to their importance.

   **Example:**

   ```css
   .grouped-content {
     border-bottom: 3px solid #f39c12; /* Adds a bold line under the title */
     margin-bottom: 20px;
     padding-bottom: 10px;
   }
   ```

   **HTML:**

   ```html
   <h2 class="grouped-content">Important Section</h2>
   <p>Content of the section...</p>
   ```

### 7. **Using CSS Borders in Grid Layouts**:
   If you use CSS Grid for layout, borders can separate the grid cells, creating clear divisions.

   **Example:**

   ```css
   .grid-container {
     display: grid;
     grid-template-columns: repeat(3, 1fr);
     gap: 10px;
   }

   .grid-item {
     border: 1px solid #ddd; /* Borders for grid items */
     padding: 10px;
   }
   ```

   **HTML:**

   ```html
   <div class="grid-container">
     <div class="grid-item">Item 1</div>
     <div class="grid-item">Item 2</div>
     <div class="grid-item">Item 3</div>
   </div>
   ```

Lines are a simple yet powerful tool for organizing content on a page. Whether you use horizontal lines to separate sections, vertical lines for columns, or dashed lines for a softer look, they help improve the readability and visual appeal of the page, especially when space is limited.

## Letter Spacing

Yes, the **`letter-spacing`** property in CSS allows you to control the space between individual characters in a text. By increasing or decreasing the value of this property, you can adjust the readability, style, and visual appeal of your text.

### Syntax:
```css
element {
  letter-spacing: value;
}
```

Where **`value`** can be:
- **`normal`**: The default spacing between characters (no change).
- **`<length>`**: A specific length value (such as `px`, `em`, `rem`, etc.), which can either increase or decrease the space between characters.

### Examples

#### 1. **Increasing Letter Spacing**:
If you want to add space between characters to make the text more spaced out (ideal for headlines or decorative text):
```css
h1 {
  letter-spacing: 2px; /* Increases the space between letters by 2px */
}
```

#### 2. **Decreasing Letter Spacing**:
If you want to decrease the space between characters (helpful for tightening text in compact layouts):
```css
h1 {
  letter-spacing: -1px; /* Decreases the space between letters by 1px */
}
```

#### 3. **Using `normal` for Default Spacing**:
If you've altered the letter spacing earlier and want to reset it back to the default:
```css
h1 {
  letter-spacing: normal; /* Resets the spacing to default */
}
```

#### 4. **Using `em` or `rem` Units for Responsive Spacing**:
You can also use relative units like `em` or `rem` for scalable letter spacing. This can be particularly useful for responsive design:
```css
h1 {
  letter-spacing: 0.1em; /* Adds space relative to the font size */
}
```

#### Visual Example:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    h1 {
      letter-spacing: 2px;
    }
  </style>
  <title>Letter Spacing Example</title>
</head>
<body>
  <h1>Spaced Out Text</h1>
  <p>This text has increased letter spacing.</p>
</body>
</html>
```

In this example, the text in the **`h1`** tag will have 2px of spacing between each letter, giving it a more spaced-out appearance.

#### Use Cases:
- **Headlines**: Increasing letter-spacing for a more open and elegant feel.
- **Buttons**: Tightening the letter-spacing to make text appear more compact and fitting within a button.
- **Branding**: Customizing letter-spacing can be part of the design to give a distinctive, clean, or modern look to a brand's typography.

