# TailwindCSS V4 Config Steps
## 1. Environment Preparation: <br/>
Install this plugin <br/>
       
![image](https://github.com/user-attachments/assets/2a5fa215-42d3-4ad7-b55a-1dde9dd274ac)

This is another extension:

![image](https://github.com/user-attachments/assets/cb20d014-8ff2-41eb-9654-2e0c207a840a)

## 2. CDN:
https://tailwindcss.com/docs/installation/play-cdn
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://unpkg.com/@tailwindcss/browser@4"></script>
</head>
<body>
    <div class="text-3xl bg-red-400">Welcome To Thailwind</div>
</body>
</html>
```

## 3. Follow this link to config tailwindcss cli<br/>
https://tailwindcss.com/docs/installation/tailwind-cli

### Sub Steps:
##### Step 3-1:
 run: npm init with all default values<br/>
##### Step 3-2:
Follow this link:  https://tailwindcss.com/docs/installation/tailwind-cli<br/>
Please notice I changed the file structure as below:<br/>
![image](https://github.com/user-attachments/assets/880e74d5-6584-4df6-8f73-978bff688abc)<br/>
##### Step 3-3:
Install the plugin:  <br/>
![image](https://github.com/user-attachments/assets/7200b937-90b0-416f-b63d-7127a14e7043)<br/>

And create an empty config file: <br/>
![image](https://github.com/user-attachments/assets/dbf0dd64-9f69-4544-b6aa-0eb423d39bc4)<br/>

##### Step 3-3:
Run:  npm run dev to open the page:<br/>
![image](https://github.com/user-attachments/assets/5554d925-08af-4492-875d-f8331c89bda5)<br/>


## 4. Html Emmet:<br/>

```html
<body>
    <!--.btn-->
    <div class="btn"></div>

    <!-- . -->
    <div class=""></div>

    <!-- .btn.text-sm-->
    <div class="btn text-sm"></div>

    <!-- #id-->
    <div id="id"></div>

    <!-- #username-->
    <div id="username"></div>

    <!-- #username.btn.test-lg-->
    <div id="username" class="btn test-lg"></div>

    <!-- span.btn -->
    <span class="btn"></span>

    <!-- ul>li -->
    <ul>
        <li></li>
    </ul>

    <!-- ul>li*3 -->
    <ul>
        <li></li>
        <li></li>
        <li></li>
    </ul>

    <!-- li+div -->
    <li></li>
    <div></div>

    <!-- ul>li*3+p -->
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <p></p>
    </ul>

    <!-- ul>li*2+p -->
    <ul>
        <li></li>
        <li></li>
    </ul>
    <p></p>
     
    <!-- p>lorem-->
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto fugiat ipsa recusandae rem numquam modi corporis illum, aut laborum ea at atque suscipit reiciendis veritatis nam doloribus incidunt animi? Velit.</p>
     
    <!-- p>lorem5-->
    <p>Lorem ipsum dolor sit amet.</p>

    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corrupti, ratione.</p>

    <!--ul>li{item}-->
    <ul>
        <li>item</li>
    </ul>

    <!-- ul>li{item$}*3 -->
    <ul>
        <li>item1</li>
        <li>item2</li>
        <li>item3</li>
    </ul>

    <!--.font-nomo.text-2xl>lorem10-->
    <div class="font-nomo text-2xl">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum repudiandae libero nisi error numquam maiores voluptate est corrupti nihil amet, at inventore consequuntur officia eius, veniam quos, autem illo quasi.</div>
</body>
```


