---
layout: page
title: Testing Forms
permalink: testing-forms/
---

<style>
  form {
    max-width: 400px;
    padding: 20px;
    background: #fafafa;
    border: 1px solid #ddd;
    border-radius: 8px;
  }

  label {
    font-weight: 600;
    display: block;
    margin-bottom: 6px;
  }

  input[type="text"],
  input[type="number"],
  select {
    width: 100%;
    padding: 8px 10px;
    margin-bottom: 16px;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 15px;
  }

  /* radio + checkbox styling */
  .inline-option {
    display: flex;
    align-items: center;
    gap: 8px;
    margin-bottom: 6px;
    font-weight: 500;
  }

  input[type="radio"],
  input[type="checkbox"] {
    transform: scale(1.2);
  }

  .group-title {
    margin: 16px 0 6px;
    font-weight: 600;
  }
</style>

# Testing Forms

<form>

<div>
    <label for="textInput">Text input:</label>
  <input type="text" id="textInput" name="textInput" placeholder="Enter text">

</div>


<div>
    <label for="numberInput">Number input:</label>
  <input type="number" id="numberInput" name="numberInput" placeholder="123">

</div>


  <div class="group-title">Choose one option:</div>

<div>
  
  <label class="inline-option">
    Option 1
    <input type="radio" name="radioGroup" value="option1">
  </label>

  </div>

  <div>
    

  <label class="inline-option">
    Option 2
    <input type="radio" name="radioGroup" value="option2">
  </label>
  </div>

<div>
  <label class="inline-option">
    Option 3
    <input type="radio" name="radioGroup" value="option3">
  </label>
</div>

  <div class="group-title">Select any options:</div>

<div>
    <label class="inline-option">
    Checkbox 1
    <input type="checkbox" name="c1" value="check1">
  </label>

</div>

<div>
    <label class="inline-option">
    Checkbox 2
    <input type="checkbox" name="c2" value="check2">
  </label>

</div>

<div>
    <label class="inline-option">
    Checkbox 3
    <input type="checkbox" name="c3" value="check3">
  </label>
</div>





<div>
    <label class="group-title" for="selectTest">Select an option:</label>
  <select id="selectTest" name="selectTest">
    <option value="a">Option A</option>
    <option value="b">Option B</option>
    <option value="c">Option C</option>
  </select>

</div>

<div>
  <button type="reset" style="
    padding: 10px 16px;
    background: #eee;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 15px;
    cursor: pointer;
    font-weight: 600;
  ">
    Reset form
  </button>
</div>

</form>




<div style="margin-top: 40px;">
  <h2>Tabuľkový formulár</h2>
  <form>
    <table style="width: 100%; border-collapse: collapse;">
      <thead>
        <tr>
          <th style="border: 1px solid #ccc; padding: 8px;">Meno</th>
          <th style="border: 1px solid #ccc; padding: 8px;">Test 1</th>
          <th style="border: 1px solid #ccc; padding: 8px;">Test 2</th>
          <th style="border: 1px solid #ccc; padding: 8px;">Test 3</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td style="border: 1px solid #ccc; padding: 8px;">Ján</td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="jan_test1" /></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="jan_test2" /></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="jan_test3" /></td>
        </tr>
        <tr>
          <td style="border: 1px solid #ccc; padding: 8px;">Eva</td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="eva_test1" /></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="eva_test2" /></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="eva_test3" /></td>
        </tr>
        <tr>
          <td style="border: 1px solid #ccc; padding: 8px;">Peter</td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="peter_test1" /></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="peter_test2" /></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="peter_test3" /></td>
        </tr>
      </tbody>
    </table>
    <div style="margin-top: 20px;">
      <button type="submit" style="padding: 10px 16px; background: #4CAF50; color: white; border: none; border-radius: 6px; font-size: 15px; cursor: pointer;">
        Odoslať výsledky
      </button>
    </div>
  </form>
</div>
