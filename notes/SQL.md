# SQL

**Summary**: Notes on SQL databases and query engines, especially spatial SQL in PostGIS and DuckDB.
**Last updated**: 2026-11-18

---

- [PostGIS spatial joins, translated to DuckDB](https://www.geomermaids.com/cookbook/duckdb-spatial/): A Geomermaids cookbook that rewrites common PostGIS spatial joins for DuckDB and compares their query plans on FEMA flood-zone polygons. Two key differences: DuckDB joins build their own run-time R-tree, and DuckDB doesn't prefilter by bounding box automatically the way PostGIS does. It also shows how to clip large GeoParquet files fast by putting literal bounding boxes in the query ([[Data]]). *Keywords: DuckDB spatial, spatial joins, R-tree index, bounding-box filtering, GeoParquet, PostGIS*
