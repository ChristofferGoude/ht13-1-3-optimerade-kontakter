### Laboration 3 - ASP.net MVC

#### Inställningar

**Punkt 1**

SQL: SELECT enamn FROM DemoMedlem.dbo.Medlem

**Punkt 2**

Resultat: "(652868 row(s) affected)".

**Punkt 3**

SET: SET STATISTICS IO ON GO

SQL: Se punkt 1.

**Punkt 4**

Resultat: 

(652868 row(s) affected)
Table 'Medlem'. Scan count 1, logical reads 40637, physical reads 0, read-ahead reads 0, lob logical reads 0, lob physical reads 0, lob read-ahead reads 0.

**Punkt 5**

SET: SET STATISTICS TIME ON GO

SQL: Se punkt 1.

**Punkt 6**

Resultat:

SQL Server parse and compile time: 
   CPU time = 0 ms, elapsed time = 0 ms.

(652868 row(s) affected)
Table 'Medlem'. Scan count 1, logical reads 40637, physical reads 0, read-ahead reads 0, lob logical reads 0, lob physical reads 0, lob read-ahead reads 0.

 SQL Server Execution Times:
   CPU time = 203 ms,  elapsed time = 12424 ms.

**Punkt 7**

Include Actual Execution Plan: ON

SQL: Se punkt 1.

**Punkt 8**

Resultat Execution Plan: 

Query 1: Query cost (realtive to the batch): 100%
SELECT enamn FROM DemoMedlem.dbo.Medlem

