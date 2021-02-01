# s
anti resubmit
```bash
<script>
    if ( window.history.replaceState ) {
        window.history.replaceState( null, null, window.location.href );
    }
</script>
```
anti xss
```bash
function xss($input) 
{
    return mysqli_real_escape_string($DB,stripslashes(strip_tags(htmlspecialchars($input,ENT_QUOTES))));

}
```
kecuali data yang di pilih
```bash

            <?php
            $datarayy = array_column($tahun, 'tahun');
            $kodeunset = array_search($row['tahun'],$datarayy);
            unset($datarayy[$kodeunset]);
            foreach($datarayy as $tahun){
            echo $tahun;
            ?>
          
```
