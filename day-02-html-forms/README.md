# Day 02 — HTML Forms

**Roadmap Phase:** 1 — Web Foundations  
**Date:** 2 May 2026

## What I Built
A contact form and a registration form using only HTML5.
Used validation attributes like required, minlength, maxlength,
min, max, and pattern — no CSS, no JavaScript.

## What I Learned
- The difference between `<input type="text">` and `<textarea>` is that the `<input type="text">` allows single line text field and `<textarea>` allows using multi-line text box.
- The `for` attribute on a `<label>` links the label to a specific input field using the input’s `id`. Clicking the label will focus or activate that input.
- The difference between `required` , `minlength` and `pattern` is `required` doesnot allows you to make field empty, `minlength` sets the minimum number of characters and `pattern`enforces a specific format using regex (e.g., only numbers, or an email style).
- The `<input type="checkbox">` attribute allows multiple selections (you can tick more than one) and `<input type="radio">` allows only one choice from a group.
- The `<input type="radio">` need the same name attribute because the `name` groups them together, without the same `name` they act like separate checkboxes and with the same `name` only one option in that group can be selected.

## Tags Used
`<form>` `<input>` `<label>` `<select>` `<option>` `<textarea>`

## Next
Day 03 — CSS basics