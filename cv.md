# **Marina Rak**
***
## **Junior Frontend Developer**
***
### **Contact information:**
* **Location:** Brest, Belarus
* **Phone:** +375298809874
* **E-mail:** rakmarina1995@gmail.com
* [LinkeId](https://www.linkedin.com/in/marina-rak-6a99b91a0?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BpltmBG1yTHCxYq9I%2FIAS1w%3D%3D)
***
### **About myself:**
I have a great desire to achieve high progress in Frontend development, so I spend all my time learning technical means and improving my soft skills.
***
### **Skills:**
* JS
* HTML&CSS
* Bootstrap/JQuery
* Git
* Figma/Photoshop
***
### **Code example:**
``` 
   $('#form_btn').click(function (e) {
        e.preventDefault();
        let elements = $('.order input');
        for (let i = 0; i < elements.length; i++) {
            if (!($(elements).eq(i).val())) {
                alert('Заполните поле ' + $(elements).eq(i).attr('name'));
                return;
            }
        }
        if (($('#inputIndex').val().length) !== 6) {
            alert('Индекс должен содержать 6 символов!');
            return;
        }
        $('#order_text').show();
        $('#form').hide();
    });
```

**One of my works:**
[https://github.com/rakmarina1995/cars-app.git](https://github.com/rakmarina1995/cars-app.git)
### **Education:**
* Brest State A.S. Pushkin University*
### **Languages:**
* English - A2 (B1 in process)