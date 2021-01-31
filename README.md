# s

```bash
<script>
    if ( window.history.replaceState ) {
        window.history.replaceState( null, null, window.location.href );
    }
</script>
```
```bash
function xss($input) 
{
    return mysqli_real_escape_string($DB,stripslashes(strip_tags(htmlspecialchars($input,ENT_QUOTES))));

}
```
