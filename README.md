# <p align="center"><font color='#FF79C6'><strong>Learn Typography by Building a Nutrition Label</strong></font></p>

<p align="center"> <i>Módulo de treinamento para a certificação <a href="https://www.freecodecamp.org/learn/2022/responsive-web-design/"><em>Responsive Web Design Certification</em></a> da plataforma FreeCodeCamp</i>.
<p>

<p align="center">
    <img src="https://skillicons.dev/icons?i=html,css,md,vscode,git,github" height="30px">
</p>


<br>

## :memo: <font color='#8BE9FD'><strong>Notas de Aula</strong></font>

<br>

### Borders

Borders in CSS are a powerful visual tool for grouping, prioritizing, and separating content within a webpage. By adding borders, you can visually organize different sections or elements, draw attention to specific areas, or simply improve the overall layout and user experience.

#### Ways to Use Borders for Grouping and Prioritizing Content:

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

### fine-tune

To fine-tune the placement of your **`h1`** element, you can adjust its margins using negative values. This will shift the element slightly in the respective directions. In this case, you want to apply a **-4px** margin to the top and bottom, and **0px** to the left and right.

Here’s the CSS rule:

```css
h1 {
  margin: -4px 0; /* -4px for top and bottom, 0px for left and right */
}
```

#### Explanation:
- **`-4px`** for the **top** and **bottom**: This will shift the `h1` slightly upwards and reduce any extra space between the `h1` and the surrounding content.
- **`0px`** for the **left** and **right**: Ensures there is no additional margin on the sides, keeping it aligned as intended.

This adjustment should help in refining the position of your `h1` element for a better visual outcome!
