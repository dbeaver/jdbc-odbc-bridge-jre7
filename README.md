# JDBC ODBC bridge driver from JRE7

JDBC-ODBC bridge driver was removed from JRE/JDK after version 7.

There is no other open-source JDBC-ODBC bridge driver in 2021. So we keep using this outdated JRE7 driver.  
It has the same License as JRE7 from Oracle.

## Using the driver in DBeaver

It was removed in DBeaver Community Edition **23.1**. 

You can start using [DBeaver PRO products](https://dbeaver.com) (they include brand new ODBC driver).  

Or, to use legacy driver in Community:

1. Download [jdbc-odbc-bridge-jre7.jar](https://github.com/dbeaver/jdbc-odbc-bridge-jre7/raw/main/jdbc-odbc-bridge-jre7.jar) and [x64/JdbcOdbc.dll](https://github.com/dbeaver/jdbc-odbc-bridge-jre7/raw/main/x64/JdbcOdbc.dll)
1. Create a new driver in DBeaver
1. Add newly downloaded files to it

For more information, see [how to add a driver in DBeaver](https://github.com/dbeaver/dbeaver/wiki/Database-drivers/#adding-driver-configuration-in-dbeaver)
