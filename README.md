<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Coffee Survey</title>
    </head>
    <body>
      <form>
        <h1>Coffee Survey</h1>
        <fieldset>
          <h2>Personal Information</h2>

        <form action="http://foo.com" method="POST">
        <legend> **Please provide your contact information** </legend>
          <h3>Full Name</h3>
          <input type= "text" name= "Full_Name" id= "Full_Name">
         <h3>Email</h3>
          <input type ="email"> </input>
          <h3>Phone Number</h3>
          <input type ="Phone Number"></input>
          </fieldset>
        </form>
        <br>
        <fieldset>
          <h2>Coffee Preferences</h2>
        <div>
          <legend> **Which style of coffee do you prefer? _(Choose 1 option)_** </legend>
            <input type= "radio" name= "coffee" id= "coffee_1" value= Espresso>
            <label for= "coffee_1">Espresso</label>
            <br>
            <input type= "radio" name= "coffee" id= "coffee_2" value= Americano>
            <label for= "coffee_2">Americano</label>
            <br>
            <input type= "radio" name= "coffee" id= "coffee_3" value= Cappuccino>
            <label for= "coffee_3">Cappuuccino</label>
            <br>
            <input type= "radio" name= "coffee" id= "coffee_4" value= Other>
            <label for= "coffee_4">Other</label>
        </div>
        <br>
        <div>
          <legend> **Do you dd anything to your coffee? _(Chheck all that apply)_** </legend>
            <input type= "checkbox" name= "coffeeSupp1" id= "coffeeSupp1" value= Sugar>
            <label for= "coffeeSupp1">Sugar</label>
            <br>
            <input type= "checkbox" name= "coffeeSupp2" id= "coffeeSupp2" value= "Artifical Sweetener">
            <label for= "coffeeSupp2">Artificial Sweetener</label>
            <br>
            <input type= "checkbox" name= "coffeeSupp3" id= "coffeeSupp3" value= Cream>
            <label for= "coffeeSupp3">Cream</label>
            <br>
            <input type= "checkbox" name= "coffeeSupp4" id= "coffeeSupp4" value= Milk>
            <label for= "coffeeSupp4">Milk</label>
            <br>
            <input type= "checkbox" name= "coffeeSupp5" id= "coffeeSupp5" value= Butter>
            <label for= "coffeeSupp5">Butter</label>
            <br>
            <input type= "checkbox" name= "coffeeSupp6" id= "coffeeSupp6" value= Water>
            <label for= "coffeeSupp6">Water</label>
        </div>
        <br>
        <div>
          <legend> **What size do you normally order? _(Choose 1 option)_** </legend>
          <select name= "cupSize" id= "cupSize">
            <option value= "Small">Small _(default)_</option>
            <option value= "Medium">Medium</option>
            <option value= "Large">Large</option>
          </select>
        </div>
        <br>
        <div>
          <legend> **How many cups of cofee do you drinkper day, on average?** </legend>
          <select name= "totalCups" id= "totalCups">
            <option value= "totalCups">Between 0-1 cups _(default)_</option>
            <option value= "totalCups">Between 2-3 cups</option>
            <option value= "totalCups">More than 3 cups</option>
          </select>
        </div>
        <br>
          <lable for= "memory">**What is you fondest memeory related to coffee?**</label>
          <textarea  name= "memory" id= "memory" cols= "30" row= "10"></textarea>
        </fieldset>
    </body>
</html>
