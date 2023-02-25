<center>
<h1>Flex container theory</h1>
</center>

- **Default behaviour of flex-container**
  - Width of a flex-item depends on the amount of content it carries.
  - Height of every single flex-item will be equal and the value of the tallest flex-item is taken into consideration.

- **Flex Gotchas**
  - Default value of align-items is stretch.
  - align-self property is used for aligning flex-item
  - Default value of order property is 0. Suppose there are multiple flex-items, -1 will shift the flex-item to the left, 1 will shift the flex-item to the right.