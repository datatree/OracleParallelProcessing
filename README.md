# OracleParallelProcessing

 This repository will explore how parallel processing works within the Oracle 12c database server and how you can monitor it.
 
    • In addition, we will cover how logging works in Oracle 12c, what options are available to us to facilitate, updates, deletes,       inserts, and CTASs on records within very large tables with minimal impact on production systems.
    • There are many solutions for these types of problems where you need to update, delete, insert and CTAS records from a table         with hundreds of millions of rows.
    • The traditional update statement can take days or months, which of us can take that kind of  rocessing hit.
    • My solution is one where I used the options nologging and parallel options to overcome these processing issues.
    • The nologging/logging different in Oracle 12c but the ‘FORCE LOGGING’ can disable the use NOLOGGING option at table level and       even though you use an ALTER TABLE command or a CREATE TABLE command, you will still be in LOGGING mode and you will not even       know it.
