# Remote Sensing

**Summary**: Notes on satellite and aerial imagery, Earth observation data products, and the tools used to analyse them.
**Last updated**: 2026-11-18

---

- [Stop using LST to quantify heat hazard (LinkedIn post)](https://www.linkedin.com/feed/update/urn:li:activity:7478690057026207745/): TC Chakraborty argues that satellite land surface temperature (LST) measures the "skin" temperature of roofs, roads and tree canopies, not the air people feel. Viral "55°C in the city" maps overstate [[Climate_Change]] heat hazard and the cooling effect of trees, which erodes trust in the science. Commenters reply that LST is still useful where air measurements are scarce, and that radiant heat matters for [[Urban_Planning]]. *Keywords: land surface temperature, air temperature, extreme heat, urban heat island, science communication, urban trees*
- [The Technical Debt of Earth Embedding Products](https://cloudnativegeo.org/blog/2026/02/the-technical-debt-of-earth-embedding-products/): Isaac Corley (CNG blog, Feb 2026) compares nine Earth [[Embeddings]] products, including AlphaEarth, Clay, Tessera and Major TOM, by resolution, dimensions, dtype and license. Because each product uses its own grid, CRS and format, they are hard to combine. The post argues for cloud-native formats ([[Data]]): GeoParquet for patch embeddings and COG or Zarr for pixel embeddings. *Keywords: Earth embeddings, AlphaEarth, GeoParquet, TorchGeo, cloud-native geospatial, foundation models*

### Related notes on other pages
- Agribound, field boundary mapping from satellite imagery. See [[Agriculture]].
