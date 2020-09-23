<div align="center">

## JavaScript Variables in PHP


</div>

### Description

This code will show you a basic example of sending a JavaScript Variable to PHP. Specifically a JavaScript prompt windows output.
 
### More Info
 
JavaScript Variable

None Known


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jeff Wright](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jeff-wright.md)
**Level**          |Advanced
**User Rating**    |4.1 (29 globes from 7 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__8-1.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jeff-wright-javascript-variables-in-php__8-601/archive/master.zip)





### Source Code

```
<script language="JavaScript">
<!-- Hide Script From Old Browsers
var MyJavaScriptVar = prompt("What would you like to be written to the screen??","Hello World!")
//-->
</script>
<? $MyPHPVar = "<script language=JavaScript> document.write(MyJavaScriptVar);</script>";
echo $MyPHPVar;
?>
```

