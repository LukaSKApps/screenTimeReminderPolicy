---
layout: page
title: Testing Forms 2
permalink: testing-forms2/
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
  input[type="tel"],
  input[type="number"],
  select {
    width: 100%;
    padding: 8px 10px;
    margin-bottom: 16px;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 15px;
  }

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

<form action="/submit-form" method="post">

  <div>
    <label for="firstName">First name</label>
    <input type="text" id="firstName" name="firstName" placeholder="Enter first name">
  </div>

  <div>
    <label for="lastName">Last name</label>
    <input type="text" id="lastName" name="lastName" placeholder="Enter last name">
  </div>

  <div>
    <label for="phone">Phone</label>
    <input type="tel" id="phone" name="phone" placeholder="+421 123 456 789">
  </div>

  <div>
    <label for="address">Address</label>
    <input type="text" id="address" name="address" placeholder="Street, city">
  </div>

  <div class="group-title">Gender</div>

  <div class="inline-option">
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label>
  </div>

  <div class="inline-option">
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label>
  </div>

  <div class="group-title">Favorite food</div>

  <div class="inline-option">
    <input type="checkbox" id="pizza" name="food[]" value="pizza">
    <label for="pizza">Pizza</label>
  </div>

  <div class="inline-option">
    <input type="checkbox" id="hamburger" name="food[]" value="hamburger">
    <label for="hamburger">Hamburger</label>
  </div>

  <div class="inline-option">
    <input type="checkbox" id="pasta" name="food[]" value="pasta">
    <label for="pasta">Pasta</label>
  </div>

  <div>
    <label class="group-title" for="country">Country</label>
    <select id="country" name="country">
      <option value="dk">Denmark</option>
      <option value="de">Germany</option>
      <option value="us">United States of America</option>
    </select>
  </div>

  <div style="display: flex; gap: 10px;">
    <button type="submit" style="
      padding: 10px 16px;
      background: #4CAF50;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 15px;
      cursor: pointer;
      font-weight: 600;
    ">
      Submit
    </button>

  <button type="reset" style="
      padding: 10px 16px;
      background: #eee;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 15px;
      cursor: pointer;
      font-weight: 600;
    ">
      Reset
    </button>
  </div>

</form>


<div style="margin-top: 40px;">
  <h2>Table Form</h2>

  <form action="/submit-results" method="post">
    <table style="width: 100%; border-collapse: collapse;">
      <thead>
        <tr>
          <th style="border: 1px solid #ccc; padding: 8px;">Name</th>
          <th style="border: 1px solid #ccc; padding: 8px;">Exam 1</th>
          <th style="border: 1px solid #ccc; padding: 8px;">Exam 2</th>
          <th style="border: 1px solid #ccc; padding: 8px;">Exam 3</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td style="border: 1px solid #ccc; padding: 8px;">John</td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="jan_test1"></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="jan_test2"></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="jan_test3"></td>
        </tr>
        <tr>
          <td style="border: 1px solid #ccc; padding: 8px;">Thomas</td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="eva_test1"></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="eva_test2"></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="eva_test3"></td>
        </tr>
        <tr>
          <td style="border: 1px solid #ccc; padding: 8px;">Peter</td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="peter_test1"></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="peter_test2"></td>
          <td style="border: 1px solid #ccc; padding: 8px;"><input type="number" name="peter_test3"></td>
        </tr>
      </tbody>
    </table>

  <div style="margin-top: 20px;">
      <button type="submit" style="
        padding: 10px 16px;
        background: #4CAF50;
        color: white;
        border: none;
        border-radius: 6px;
        font-size: 15px;
        cursor: pointer;
      ">
        Save/Reset
      </button>
    </div>
  </form>
</div>
