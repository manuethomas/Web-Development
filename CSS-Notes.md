## Position

### Relative

- **Positioning Context** : Element position relative to its original position in the document flow

- **Offset Properties** : - top, right, bottom, left

- **Effect on Layout** : - The element remains in the normal document flow, so it still takes up space as if it were not positioned

### Absolute

- **Positioning Context** : Element positioned relative to its nearest positioned ancestor (an ancestor with a position value other than static). If no such ancestor exists, it is positioned relative to the initial containing block (usually the $<body>$ element)


- **Offset Properties** - top, right, bottom, left

- **Effect on Layout** : The element is removed from the normal document flow, so it does not take up space and can overlap other elements

