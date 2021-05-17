# shiny_bookmarking

When you click the "BOOKMARK" button, a folder with a GUID is created.
Within the folder there is an `input.RDS`, a list of the reactive values. 

```
$delta
[1] 1

$length
[1] 100

$omega
[1] 1

$damping
[1] 1
```

We can use `http://127.0.0.1:3645/?_state_id_=GUID` to restore that state. <span style="color:orangered;"> 
Can we hack this? Rather than read an RDS just use a list object to restore the app state?</span>
