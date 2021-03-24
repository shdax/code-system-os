# code-system-os
Bahasa pemrograman yang dapat menggunakan execute UNIX

### Python
```
import os
os.system('uname -a')
```

### Perl
```
$ perl -e 'print `uname -a`'
```

### PHP
```
<?php
$result = shell_exec('uname -a');
echo "<pre>$result</pre>";
?>
```

### Ruby
```
$ ruby -e 'puts `uname -a`'
```

### Node
```
$ node -e 'var exec = require("child_process").exec;
exec("uname -a", function (error, stdOut, stdErr) {
console.log(stdOut);
});'
```
