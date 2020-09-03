# VAB Centralist

[nieuw ticket aanmaken](nieuwticket.md)

[lopende tickets](tester.html)

<script>
$(document).ready(function(){

var json = [{"name": "name1","score":"30"},{"name": "name2","score":"50"}];
//while running this code the template will be appended in your div with json data
$("#tbody").jPut({
    jsonData:json,
    //ajax_url:"youfile.json",  if you want to call from a json file
    name:"tbody_template",
});

});
</script>   

<div jput="tbody_template">
 <tr>
  <td>{{name}}</td>
  <td>{{score}}</td>
 </tr>
</div>

<table>
 <tbody id="tbody">
 </tbody>
</table>

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
