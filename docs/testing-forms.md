---
layout: page
title: Testing Forms
permalink: testing-forms/
---

# Testing Forms

<form>

  <!-- Text input -->
  <label for="textInput">Text input:</label><br>
  <input type="text" id="textInput" name="textInput" placeholder="Enter text"><br><br>

  <!-- Number input -->
  <label for="numberInput">Number input:</label><br>
  <input type="number" id="numberInput" name="numberInput" placeholder="123"><br><br>

  <!-- Radio buttons -->
  <p>Choose one option:</p>
  <input type="radio" id="r1" name="radioGroup" value="option1">
  <label for="r1">Option 1</label><br>

  <input type="radio" id="r2" name="radioGroup" value="option2">
  <label for="r2">Option 2</label><br>

  <input type="radio" id="r3" name="radioGroup" value="option3">
  <label for="r3">Option 3</label><br><br>

  <!-- Checkboxes -->
  <p>Select any options:</p>
  <input type="checkbox" id="c1" name="c1" value="check1">
  <label for="c1">Checkbox 1</label><br>

  <input type="checkbox" id="c2" name="c2" value="check2">
  <label for="c2">Checkbox 2</label><br>

  <input type="checkbox" id="c3" name="c3" value="check3">
  <label for="c3">Checkbox 3</label><br><br>

  <!-- Select -->
  <label for="selectTest">Select an option:</label><br>
  <select id="selectTest" name="selectTest">
    <option value="a">Option A</option>
    <option value="b">Option B</option>
    <option value="c">Option C</option>
  </select>

</form>
