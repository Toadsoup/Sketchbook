

###### Regex Remove All except Digits
$output = preg_replace("/\D/", "", $input);

###### Regex Remove All except Words, spaces, and dashes
$output = preg_replace("/[^ \w-]/", "", $input);
