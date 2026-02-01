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

  input[type="radio"],
  input[type="checkbox"] {
    margin-right: 6px;
    transform: scale(1.2);
  }

  .group-title {
    margin: 16px 0 6px;
    font-weight: 600;
  }
</style>

# Testing Forms

<form>

  <label for="textInput">Text input:</label>
  <input type="text" id="textInput" name="textInput" placeholder="Enter text">

  <label for="numberInput">Number input:</label>
  <input type="number" id="numberInput" name="numberInput" placeholder="123">

  <div class="group-title">Choose one option:</div>
  <div>
  <input type="radio" name="radioGroup" value="option1"><label> Option 1</label><br>
    
  </div>
  <div>
    <input type="radio" name="radioGroup" value="option2">  <label>Option 2</label><br>
  </div>

 <div>
 <input type="radio" name="radioGroup" value="option3"> <label> Option 3</label>
  
 </div>

  <div class="group-title">Select any options:</div>
  <input type="checkbox" name="c1" value="check1"><label> Checkbox 1</label><br>
  <input type="checkbox" name="c2" value="check2"><label> Checkbox 2</label><br>
  <input type="checkbox" name="c3" value="check3"><label> Checkbox 3</label>

  <label class="group-title" for="selectTest">Select an option:</label>
  <select id="selectTest" name="selectTest">
    <option value="a">Option A</option>
    <option value="b">Option B</option>
    <option value="c">Option C</option>
  </select>

</form>
