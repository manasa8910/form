
# Assignment 3 - Form 



## 🔗 Links
[Git hub repo link](https://github.com/manasa8910/form)

[Hoisted link](https://manasa8910.github.io/form/)


## HTML

#### Please refer the index.html file in the github repo


The first 3 fields of the form is created using input tag of type text.

![image](https://github.com/manasa8910/form/assets/67619299/1cf30c68-0e55-45c5-bd2a-ce25515dae93)

```bash
<form>     
    <fieldset>
        <legend>Personal Details</legend>
        <label> Firstname </label>         
        <input type="text" name="firstname" size="15"/> <br> <br>
        <label> Middlename: </label>     
        <input type="text" name="middlename" size="15"/> <br> <br>  
        <label> Lastname: </label>         
        <input type="text" name="lastname" size="15"/> <br> <br>  
```

The dropdown field of courses is created using select tag

![image](https://github.com/manasa8910/form/assets/67619299/f978ed2b-d6b3-41cd-aec8-155a305a9483)


```bash
        <label>Course :</label>   
        <select>  
        <option value="Course">Course</option>  
        <option value="BCA">BCA</option>  
        <option value="BBA">BBA</option>  
        <option value="B.Tech">B.Tech</option>  
        <option value="MBA">MBA</option>  
        <option value="MCA">MCA</option>  
        <option value="M.Tech">M.Tech</option>  
        </select>  <br>  <br>
```

The Gender field is created using input tag of type radio

![image](https://github.com/manasa8910/form/assets/67619299/16c77631-4a7c-4e4e-b514-d2085ef4ab76)

```bash
        <label> Gender : </label for="gender" ><br>  
        <input type="radio" name="gender"/> Male <br>  
        <input type="radio" name="gender"/> Female <br>  
        <input type="radio" name="gender"/> Other  <br> <br>
```

The DOB field is created using input tag of type datetime-local

![image](https://github.com/manasa8910/form/assets/67619299/9558c44a-ead6-4db1-98b2-40e96b6cc532)

```bash
        <label >DOB</label>
        <input type="datetime-local"> <br> <br>
```

The Phone field is created using input tag of type tel

![image](https://github.com/manasa8910/form/assets/67619299/2bf482d7-ef90-48a2-8ea2-570863697cbc)

```bash
        <label> Phone : </label>  
        <input type="text" name="country code"  value="+91" size="2" disabled/>   
        <input type="tel" name="phone" maxlength="10"  size="10"/> <br> <br>  
```

The Address field is created using textarea tag

![image](https://github.com/manasa8910/form/assets/67619299/fbbcf065-de0c-4694-94fa-a822c6f039c5)

```bash
        <label for="">Address : </label> <br>  
        <textarea cols="80" rows="5" value="address"> </textarea>  <br> <br>  
```

The Email field is created using input type with type email and password

![image](https://github.com/manasa8910/form/assets/67619299/f3ecb6df-b0a5-4849-82a2-572ddd775e86)

```bash
        <label>Email:</label> 
        <input type="email" id="email" name="email"/> <br> <br>  
        <label for="">Password:</label>
        <input type="Password" id="pass" name="pass"> <br> <br>  
        <label for="">Re-type password:</label>  
        <input type="Password" id="repass" name="repass"> <br> <br>  
```

Agree to terms and conditions field is created using input type with type checkbox

![image](https://github.com/manasa8910/form/assets/67619299/1349025b-a667-4843-b2a0-72f0d3e2c337)

```bash
        <input type="checkbox" />Agree to terms and conditions
        <br><br> 
```

Upload file field is created using input type with type file

![image](https://github.com/manasa8910/form/assets/67619299/b3c25f34-e8d4-4d25-b540-91c3a05f9f9c)

```bash
        <label >Choose File</label>
        <input type="file">
        <br><br>
```

Color field is created using input type with type color

![image](https://github.com/manasa8910/form/assets/67619299/9f97c39c-9b40-49b9-808c-4c89f997c632)

```bash
        <label>Choose Color</label>
        <input type="color">
        <br><br>
```

The Submit fields is created using input type with type reset and button

![image](https://github.com/manasa8910/form/assets/67619299/f23d904f-0ba7-4c6b-a7c9-bc8cc1a490bd)

```bash
        <input type="reset" value="Reset"/> 
        <input type="button" value="Submit"/>  
```
