# CS230 Questions

## Q1

a)
[link](http://www.standardista.com/css3/css-specificity/)

last part [link] (https://developer.mozilla.org/en-US/docs/Learn/CSS/Howto/Generated_content)


b)

[link] (https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX/Getting_Started)
```javascript
$.get("/resource", (json) => {console.log(json)});
$.post("/resource", jsonToBeSent, (responseJson) => {console.log(responseJSon)});

last part:
$.post("\resource", form.serialize(), (res) => {});
```

c)
[link1] (https://www.cs.uct.ac.za/mit_notes/web_programming/html/ch20s07.html)
[link2] (https://dzone.com/articles/pros-and-cons-of-ajax)
[link3] (https://status200.net/what-is-ajax/)
[link4] (https://blog.seekdotnet.com/asp-net/advantages-disadvantages-of-asp-net-ajax-hosting/)

part 2:
```javascript
function callAjax(url, data,callback){
    var xmlhttp;
    // compatible with IE7+, Firefox, Chrome, Opera, Safari
    xmlhttp = new XMLHttpRequest();
    http.setRequestHeader('Content-type', 'application/json');
    xmlhttp.onreadystatechange = function(){
        if (xmlhttp.readyState == 4 && xmlhttp.status == 200){
            callback(xmlhttp.responseText);
        }
    }
    xmlhttp.open("post", url,true);
    
    xmlhttp.send(data);
}

callAjax("\fetchData", (json) =>{
    let firstName = document.getElementById("firstName")
    .setText(json.user.firstName)
})
```

part 3:

```javascript
&.post("resource", whatWeSend, (res) => {
    $("#firstName").text(res.user.firstName)
})

```

d) 

[link1] (https://lazaroibanez.com/difference-between-the-http-requests-post-and-get-3b4ed40164c1)

[link2] (https://www.w3schools.com/tags/ref_httpmethods.asp)

[link3] (https://www.diffen.com/difference/GET-vs-POST-HTTP-Requests)

[link4] (https://www.guru99.com/difference-get-post-http.html)

[link5] (https://www.freecodecamp.org/news/http-request-methods-explained/)

find the rest idk

# 

e) 

[link1] (https://stackoverflow.com/questions/2190737/what-is-the-difference-between-mysql-mysqli-and-pdo#:~:text=MySQLi%20is%20a%20replacement%20for,MySQL%20among%20many%20other%20databases)

[link2] (https://codeanddeploy.com/blog/php/php-pdo-insert-multiple-rows-example)



# 

