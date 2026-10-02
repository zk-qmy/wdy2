# Main Concepts — Module 6, Lesson 1: Containers

1. **`<div>` containers**

   * `<div>` is used to **combine multiple objects into one block/container**.
   * It helps apply styles to a group of elements together. 

2. **Nesting HTML elements**

   * A container can have **child elements** inside it.
   * Example: `<div>` can contain `<h2>`, `<p>`, and `<img>`.
   * `<p>` should not be used as a container for headings and other blocks because its purpose is a text paragraph. 

3. **Block vs. Inline objects**

   * **Block:** starts on a new line and normally takes the available width.
   * **Inline:** stays on the same line as long as there is enough space. 

4. **Controlling size**

   * `width` and `height` can control the size of elements.
   * For a block, the total space it takes includes:
     **content + padding + border + margin**. 

5. **CSS `float`**

   * `float: left` attaches a block to the **left edge** of its parent.
   * `float: right` attaches it to the **right edge**.
   * Other objects can then appear next to the floated block. 

6. **Creating columns / side-by-side blocks**

   * Put blocks inside a common container.
   * Use `float: left` and `float: right` to place them horizontally. 

7. **Main design rule**

   * Organize website information into **separate blocks**.
   * Identical blocks can be arranged **horizontally** to create layouts such as news cards or columns. 
---
# Intial
`index.html`

# Practice
* Change <p> to <div> for container
* Set size for object
Example:
```
.img_center {

border: 4px solid
blueviolet;

}

<div class="div_light">

<h2>Wanna
upgrade...</h2>

<p>Check out the
latest...</p>

<img/><img
class="img_center"/><img/>

</div>
```
```
.div_light {

background-color: lightyellow;

}

h2 {

color: blueviolet;

width: 270px;

border-bottom: 3px dotted
blueviolet;

}

p {

width: 350px;

}
```