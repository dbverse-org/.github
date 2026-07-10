<img src="./assets/dbverse-logo.svg" alt="dbverse logo" width="180" align="right">

# dbverse

**Object-relational mappings for scientific analytics.**

*dbverse* is an open-source ecosystem for working with larger-than-memory scientific
data with analytical databases.

[Learn more](https://dbverse-org.github.io/dbverse/) ·
[R packages](https://dbverse-org.r-universe.dev/) ·
[GitHub repositories](https://github.com/orgs/dbverse-org/repositories)

<br clear="right">

---

## Core libraries

<table>
<tr>
<td width="50%" valign="top">

### [dbProject](https://github.com/dbverse-org/dbproject-r)

Project directories, connection lifecycle, pinned resources, and
database-backed data objects.

[R source](https://github.com/dbverse-org/dbproject-r) ·
[R reference](https://dbverse-org.github.io/dbproject-r/)

</td>
<td width="50%" valign="top">

### [dbMatrix](https://github.com/dbverse-org/dbmatrix-r)

Sparse and dense matrix operations that keep large arrays in an analytical
database.

[R source](https://github.com/dbverse-org/dbmatrix-r) ·
[R reference](https://dbverse-org.github.io/dbmatrix-r/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [dbSpatial](https://github.com/dbverse-org/dbspatial-r)

Spatial geometry data loading, geometry operations, measurements, and joins.

[R source](https://github.com/dbverse-org/dbspatial-r) ·
[R reference](https://dbverse-org.github.io/dbspatial-r/)

</td>
<td width="50%" valign="top">

### [dbSequence](https://github.com/dbverse-org/dbsequence-r)

Genomic data ingestion, lazy ranges, overlap filtering, and coverage over
database-backed data.

[R source](https://github.com/dbverse-org/dbsequence-r) ·

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### dbVisuals

Visualization workspace for database-backed data.

**Incubating**

</td>
</tr>
</table>

## Language availability

The documentation is organized around scientific capabilities, with matching
language examples as each implementation becomes available.

| Language | Status | Package index |
|:--|:--|:--|
| R | Available | [R-universe](https://dbverse-org.r-universe.dev/) and the package references above |
| Python | **Incubating** | - |
| Julia | **Incubating** | - |

## Built with *dbverse*

### [GiottoDB](https://github.com/dbverse-org/GiottoDB)

R package that extends the Giotto spatial framework for database-backed spatial omics data analysis.