# Bangladesh Districts with Coordinates

This file lists the 64 districts of Bangladesh, sorted alphabetically, along with their approximate latitude and longitude coordinates (in decimal degrees) for the district headquarters (zila sadar) or central point. These coordinates are intended for use in the Army IBA Sylhet Student Home District Map project, an interactive web app visualizing AIBA Sylhet students’ home districts.  

**Note**: Coordinates are sourced from reliable datasets (e.g., latlong.net, geodatos.net). Where exact headquarters coordinates are unavailable, approximate district centroids are used and noted. Always verify coordinates before using in production.  

## District Coordinates

| District Name   | Latitude  | Longitude |
|-----------------|-----------|-----------|
| Bagerhat        | 22.6596   | 89.7853   |
| Bandarban       | 22.1953   | 92.2187   |
| Barguna         | 22.1591   | 90.1266   |
| Barisal         | 22.7029   | 90.3698   |
| Bhola           | 22.6879   | 90.6441   |
| Bogra           | 24.8481   | 89.3730   |
| Brahmanbaria    | 23.9571   | 91.1119   |
| Chandpur        | 23.2323   | 90.6631   |
| Chattogram      | 22.3375   | 91.8380   |
| Chuadanga       | 23.6410   | 88.8494   |
| Comilla         | 23.4619   | 91.1850   |
| Cox's Bazar     | 21.4397   | 92.0096   |
| Dhaka           | 23.7104   | 90.4074   |
| Dinajpur        | 25.6279   | 88.6378   |
| Faridpur        | 23.6011   | 89.8333   |
| Feni            | 23.0159   | 91.3976   |
| Gaibandha       | 25.3293   | 89.5425   |
| Gazipur         | 23.9999   | 90.4203   |
| Gopalganj       | 23.0051   | 89.8266   |
| Habiganj        | 24.3740   | 91.4155   |
| Jamalpur        | 24.9196   | 89.9481   |
| Jessore         | 23.1697   | 89.2131   |
| Jhalokati       | 22.6423   | 90.1987   |
| Jhenaidah       | 23.5448   | 89.1533   |
| Joypurhat       | 25.1015   | 89.0227   |
| Khagrachari     | 23.1193   | 91.9842   |
| Khulna          | 22.8158   | 89.5644   |
| Kishoreganj     | 24.4399   | 90.7860   |
| Kurigram        | 25.8072   | 89.6291   |
| Kushtia         | 23.9013   | 89.1221   |
| Lakshmipur      | 22.9443   | 90.8299   |
| Lalmonirhat     | 25.9122   | 89.4460   |
| Madaripur       | 23.1710   | 90.2094   |
| Magura          | 23.4871   | 89.4198   |
| Manikganj       | 23.8617   | 90.0003   |
| Meherpur        | 23.7724   | 88.6318   |
| Maulvibazar     | 24.4889   | 91.7708   |
| Munshiganj      | 23.5502   | 90.5305   |
| Mymensingh      | 24.7469   | 90.4074   |
| Naogaon         | 24.7936   | 88.9318   |
| Narail          | 23.1725   | 89.5127   |
| Narayanganj     | 23.6238   | 90.5000   |
| Narsingdi       | 23.9228   | 90.7177   |
| Natore          | 24.4102   | 89.0003   |
| Nawabganj       | 24.5903   | 88.2710   |
| Netrokona       | 24.8702   | 90.7290   |
| Nilphamari      | 25.9316   | 88.8560   |
| Noakhali        | 22.8358   | 91.1017   |
| Pabna           | 24.0064   | 89.2372   |
| Panchagarh      | 26.3351   | 88.5577   |
| Patuakhali      | 22.3596   | 90.3299   |
| Pirojpur        | 22.5841   | 89.9752   |
| Rajbari         | 23.7574   | 89.6440   |
| Rajshahi        | 24.3740   | 88.6011   |
| Rangamati       | 22.6430   | 92.1919   |
| Rangpur         | 25.7468   | 89.2508   |
| Satkhira        | 22.7082   | 89.0705   |
| Shariatpur      | 23.2423   | 90.4348   |
| Sherpur         | 25.0208   | 90.0153   |
| Sirajganj       | 24.4534   | 89.7007   |
| Sunamganj       | 25.0658   | 91.3959   |
| Sylhet          | 24.8918   | 91.8837   |
| Tangail         | 24.2514   | 89.9167   |
| Thakurgaon      | 26.0338   | 88.4617   |

## Notes
- **Source**: Coordinates are primarily sourced from latlong.net and geodatos.net, cross-checked for accuracy. Some coordinates (e.g., Barguna, Jhalokati) are approximate centroids due to limited headquarters data.[](https://www.latlong.net/category/districts-19-16.html)[](https://www.geodatos.net/en/coordinates/bangladesh)
- **Usage**: These coordinates are suitable for the Mapbox app to plot student home districts. Ensure compatibility with your GeoJSON format (e.g., `{ "name": "", "batch": "", "district": "", "latitude": "", "longitude": "", "email": "" }`).
- **Verification**: Before using in production, verify coordinates, especially for districts marked as approximate, using local knowledge or additional GIS data.
- **Contributing**: If you have more precise coordinates or corrections, please submit a pull request to the GitHub repository.
