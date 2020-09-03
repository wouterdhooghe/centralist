# VAB Centralist

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeOlva0dwgnuLdJOz_U_GPd6t6oQQ05XAa3hmjuqdqa2DBUCQ/viewform?usp=pp_url&entry.771913914=Personenvervoer&entry.677900382=VAB" width="640" height="1539" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>



---

[testerding](url/tester.html)

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
