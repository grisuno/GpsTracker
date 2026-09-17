# Subsystem: php

## servers/php/dbconnect.php
- Layer: utility
- Language: php
- Imported by: `servers/php/deleteroute.php`, `servers/php/getallroutesformap.php`, `servers/php/getrouteformap.php`, `servers/php/getroutes.php`, `servers/php/updatelocation.php`, `servers/tk103/tk103-server.php`

## servers/php/deleteroute.php
- Layer: presentation
- Language: php
- Depends on: `servers/php/dbconnect.php`

## servers/php/displaymap-blue.php
- Layer: infrastructure
- Language: php

## servers/php/displaymap-dark.php
- Layer: infrastructure
- Language: php

## servers/php/displaymap.php
- Layer: infrastructure
- Language: php

## servers/php/getallroutesformap.php
- Layer: presentation
- Language: php
- Depends on: `servers/php/dbconnect.php`

## servers/php/getrouteformap.php
- Layer: presentation
- Language: php
- Depends on: `servers/php/dbconnect.php`

## servers/php/getroutes.php
- Layer: presentation
- Language: php
- Depends on: `servers/php/dbconnect.php`

## servers/php/updatelocation.php
- Layer: utility
- Language: php
- Depends on: `servers/php/dbconnect.php`
