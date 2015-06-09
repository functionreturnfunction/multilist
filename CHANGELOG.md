## 0.8.2

- Copies any data-* HTML5 attributes from the target div to the hidden input that gets rendered (useful for validation and such)

## 0.8.3

- Removes the 'name' attribute from the target div, which was causing a weird issue with jquery/.Net MVC unobtrusive validation

## 0.9.0

- Collapsable area is now detached so that it can still be visible if the target div is inside a container that's overflow:hidden

## 0.9.1

- Fixed a positioning issue when an ancestor has margin/padding/offset

## 0.9.2

- If mode is single and an item is selected when the page loads, the item gets clicked so the value is actually set.

## 0.9.3

- Added clear method to reset a multilist.

## 0.9.4

- Fixed multilist methods being called when the selector has no elements. 

## 0.9.5

- Fixed bad push of 0.9.4 tag without running grunt release.