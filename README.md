# Triplet Network for Self Supervised Location Embedding
## Description
This repository contains the report submitted for my Master thesis at EPFL in March 2019. This research was supervised by Olivier Verscheure, executive director at the **Swiss Data Science Center** and Jean-Philippe Nantel, team director at the **Computer Research Institute of Montreal**.
## Abstract
This work presents a method to generate embeddings that capture the semantic characteristics
of geographic locations and their surroundings. To this end, a triplet network is trained in a
self-supervised manner and with unlabelled raster data to learn a similarity metric between
locations and encode them in vectors of floating point numbers. Combining raster data
generated from OpenStreetMap and automated features engineering allows the embeddings
to capture complex semantic information hidden in a latent dimension. It is demonstrated
that our model can generate meaningful embeddings for tens of thousands of locations all
over the province of Québec. Finally, a typical use-case is presented where these embeddings
are used as additional features in a properties price prediction problem.
## Visualization
Images speak a thousand words. Here is [a visualization of embedded locations reduced in a 3-dimensional metric space.](https://www.youtube.com/playlist?list=PLUJqCVl-5yI_HeKxUBkF8eYL-nSmzSyz1)
