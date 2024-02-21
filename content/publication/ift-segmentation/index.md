---
title: 'First experiments using the image foresting transform (IFT) algorithm for segmentation of remote sensing imagery'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anderson Reis Soares
  - Thales Sehn Körting
  - Leila Maria Garcia Fonseca

date: '2013-07-01T00:00:00Z'
doi: '10.3990/2.441'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-20T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *GEOBIA 2016 Conference*

abstract: Image segmentation is a traditional method in Remote Sensing and a fundamental problem in image processing applications. It has been widely used, especially with the emergence of the Geographic Object-Based Image Analysis (GEOBIA). The results of segmentation must create uniform areas, which must allow a simpler interpretation by the users and simpler representation for classification algorithms. Several algorithms were proposed through the years, using different approaches. One that is widely used in Remote Sensing applications is the Multiresolution algorithm, that is based on the region growing method. Other, which has great potential and is applied in other research areas, is available on the Image Foresting Transform (IFT) framework, which has several image operators developed primarily for medical images. The Watershed from Grayscale Marker operator uses an edge image to perform the seg-mentation, however, we propose an extension of the edge detection algorithm, by summing normalized gradients of each band. This work aims to evaluate and compare these two segmentation algorithms, by comparing their results through supervised segmentation from reference regions, that were defined manually by an expert user. Quality measures were evaluated by four metrics, that represent the positional adjustment based the center of gravity, intensities, size, and the amount of overlap between the segment created by the algorithms and the reference segment. We selected 21 objects of a WorldView-2 multispectral image that were used to compute the metrics. Both methods reached similar results, by comparing the aforementioned 4 metrics applied to the 21 reference regions, IFT achieved better results for majority of regions. The IFT generated segments with similar shape when compared with the references, and the multiresolution generated results with similar sizes and positional adjustments. It may be explained by the fact that IFT uses an edge image to perform the segmentation. Both algorithms obtained similar agreement for intensity.

tags:
- Graphs
- Image segmentation

# Display this page in the Featured widget?
featured: false

---
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

