```ubuntudesktop@ubuntu:~$ cd Downloads
ubuntudesktop@ubuntu:~/Downloads$ cd CNA350-master/maxscale
ubuntudesktop@ubuntu:~/Downloads/CNA350-master/maxscale$ sudo docker-compose up -d
[sudo] password for ubuntudesktop: 
Starting maxscale_master2_1 ... 
Starting maxscale_master_1 ... 
Starting maxscale_master2_1
Starting maxscale_master_1 ... done
Starting maxscale_slave1_1 ... 
Starting maxscale_master2_1 ... done
Starting maxscale_slave2_1 ... 
Starting maxscale_slave2_1 ... done
Starting maxscale_maxscale_1 ... 
Starting maxscale_maxscale_1 ... done
phpmyadmin is up-to-date

Output of command 
mysql -u maxuser -pmaxpwd -h 127.0.0.1 -P 3306 -e "SELECT *  FROM zipcodes_one.zipcodes_one LIMIT 50;"
+---------+-------------+--------------------+-------+--------------+-----------+------------+-----------------------------+---------------+-----------------+---------------------+------------+
| Zipcode | ZipCodeType | City               | State | LocationType | Coord_Lat | Coord_Long | Location                    | Decommisioned | TaxReturnsFiled | EstimatedPopulation | TotalWages |
+---------+-------------+--------------------+-------+--------------+-----------+------------+-----------------------------+---------------+-----------------+---------------------+------------+
|     705 | STANDARD    | AIBONITO           | PR    | PRIMARY      | 18.14     | -66.26     | NA-US-PR-AIBONITO           | FALSE         |                 |                     |            |
|     610 | STANDARD    | ANASCO             | PR    | PRIMARY      | 18.28     | -67.14     | NA-US-PR-ANASCO             | FALSE         |                 |                     |            |
|     611 | PO BOX      | ANGELES            | PR    | PRIMARY      | 18.28     | -66.79     | NA-US-PR-ANGELES            | FALSE         |                 |                     |            |
|     612 | STANDARD    | ARECIBO            | PR    | PRIMARY      | 18.45     | -66.73     | NA-US-PR-ARECIBO            | FALSE         |                 |                     |            |
|     601 | STANDARD    | ADJUNTAS           | PR    | PRIMARY      | 18.16     | -66.72     | NA-US-PR-ADJUNTAS           | FALSE         |                 |                     |            |
|     631 | PO BOX      | CASTANER           | PR    | PRIMARY      | 18.19     | -66.82     | NA-US-PR-CASTANER           | FALSE         |                 |                     |            |
|     602 | STANDARD    | AGUADA             | PR    | PRIMARY      | 18.38     | -67.18     | NA-US-PR-AGUADA             | FALSE         |                 |                     |            |
|     603 | STANDARD    | AGUADILLA          | PR    | PRIMARY      | 18.43     | -67.15     | NA-US-PR-AGUADILLA          | FALSE         |                 |                     |            |
|     604 | PO BOX      | AGUADILLA          | PR    | PRIMARY      | 18.43     | -67.15     | NA-US-PR-AGUADILLA          | FALSE         |                 |                     |            |
|     605 | PO BOX      | AGUADILLA          | PR    | PRIMARY      | 18.43     | -67.15     | NA-US-PR-AGUADILLA          | FALSE         |                 |                     |            |
|     703 | STANDARD    | AGUAS BUENAS       | PR    | PRIMARY      | 18.25     | -66.1      | NA-US-PR-AGUAS BUENAS       | FALSE         |                 |                     |            |
|     704 | STANDARD    | AGUIRRE            | PR    | PRIMARY      | 17.96     | -66.22     | NA-US-PR-AGUIRRE            | FALSE         |                 |                     |            |
|    7675 | STANDARD    | WESTWOOD           | NJ    | PRIMARY      | 40.98     | -74.03     | NA-US-NJ-WESTWOOD           | FALSE         | 13245           | 24083               | 1089095041 |
|    7677 | STANDARD    | WOODCLIFF LAKE     | NJ    | PRIMARY      | 41.02     | -74.05     | NA-US-NJ-WOODCLIFF LAKE     | FALSE         | 2945            | 5471                | 325436960  |
|    7885 | STANDARD    | WHARTON            | NJ    | PRIMARY      | 40.89     | -74.58     | NA-US-NJ-WHARTON            | FALSE         | 5273            | 8999                | 240827990  |
|    7981 | STANDARD    | WHIPPANY           | NJ    | PRIMARY      | 40.82     | -74.41     | NA-US-NJ-WHIPPANY           | FALSE         | 4585            | 8057                | 292096795  |
|    7999 | STANDARD    | WHIPPANY           | NJ    | PRIMARY      | 40.82     | -74.41     | NA-US-NJ-WHIPPANY           | FALSE         |                 |                     |            |
|    8888 | PO BOX      | WHITEHOUSE         | NJ    | PRIMARY      | 40.62     | -74.76     | NA-US-NJ-WHITEHOUSE         | FALSE         |                 |                     |            |
|    8889 | STANDARD    | WHITEHOUSE STATION | NJ    | PRIMARY      | 40.6      | -74.76     | NA-US-NJ-WHITEHOUSE STATION | FALSE         | 4691            | 8570                | 401312434  |
|    7095 | STANDARD    | WOODBRIDGE         | NJ    | PRIMARY      | 40.55     | -74.28     | NA-US-NJ-WOODBRIDGE         | FALSE         | 10018           | 17272               | 528315021  |
|    7481 | STANDARD    | WYCKOFF            | NJ    | PRIMARY      | 40.99     | -74.16     | NA-US-NJ-WYCKOFF            | FALSE         | 8079            | 15208               | 896273759  |
|   10451 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 19434           | 31477               | 471446942  |
|   10452 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 33517           | 56277               | 723508523  |
|   10453 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 34152           | 57691               | 699611756  |
|   10454 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 13139           | 22387               | 273119576  |
|   10455 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 14914           | 25139               | 325274189  |
|   10456 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 34793           | 58750               | 732907466  |
|   10457 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 29023           | 48779               | 614273091  |
|   10458 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 29920           | 50085               | 693447254  |
|   10459 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 17977           | 30434               | 414021653  |
|   10460 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 23466           | 39507               | 531807385  |
|   10461 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 21862           | 35421               | 839765651  |
|   10462 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 35620           | 57854               | 1197519842 |
|   10463 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 31592           | 50313               | 1284853119 |
|   10464 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 2131            | 3381                | 108256016  |
|   10465 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 18686           | 30798               | 817052868  |
|   10466 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 29153           | 47658               | 924776075  |
|   10467 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 39540           | 64907               | 1114305720 |
|   10468 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 34706           | 55824               | 840612915  |
|   10469 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 28964           | 47625               | 1017556583 |
|   10470 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 7000            | 10880               | 260963512  |
|   10471 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 9876            | 15606               | 623827705  |
|   10472 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 26025           | 43761               | 630416228  |
|   10473 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 26122           | 42812               | 817850845  |
|   10474 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 4369            | 7377                | 97578251   |
|   10475 | STANDARD    | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         | 21124           | 31659               | 740068715  |
|   10499 | UNIQUE      | BRONX              | NY    | PRIMARY      | 40.84     | -73.87     | NA-US-NY-BRONX              | FALSE         |                 |                     |            |
|   10001 | STANDARD    | NEW YORK           | NY    | PRIMARY      | 40.71     | -73.99     | NA-US-NY-NEW YORK           | FALSE         | 12534           | 16553               | 1031960117 |
|   10002 | STANDARD    | NEW YORK           | NY    | PRIMARY      | 40.71     | -73.99     | NA-US-NY-NEW YORK           | FALSE         | 45236           | 70604               | 1394042364 |
|   10003 | STANDARD    | NEW YORK           | NY    | PRIMARY      | 40.71     | -73.99     | NA-US-NY-NEW YORK           | FALSE         | 28817           | 36569               |            |
+---------+-------------+--------------------+-------+--------------+-----------+------------+-----------------------------+---------------+-----------------+---------------------+------------+
```
