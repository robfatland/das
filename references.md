## USGS article: Seismology in the cloud; a new streaming workflow

MacCarthy, Jonathan, Marcillo, Omar, Trabant, Chad

Seismological research letters, 2020, Vol.91 (3), p.1804-1812

#### Description

Data-intensive research in seismology is experiencing a recent boom, driven in part by large 
volumes of available data and advances in the growing field of data science. However, there 
are significant barriers to processing large data volumes, such as long retrieval times from 
data repositories, complex data management, and limited computational resources. New tools 
and platforms have reduced the barriers to entry for scientific cluster computing, including 
the maturation of the commercial cloud as an accessible instrument for research. In this 
work, we build a customized research cluster in the cloud to test a new workflow for 
large-scale seismic analysis, in which data are processed as a stream (retrieved on-the-fly 
and acted upon without storing), with data from the Incorporated Research Institutions 
for Seismology Data Management Center. We use this workflow to deploy a spectral peak 
detection algorithm over 5.6 TB of compressed continuous seismic data from 2074 stations 
of the USArray Transportable Array EarthScope network. Using a 50-node cluster in the 
cloud, we completed the noise survey in 80 hr, with an average data throughput of 1.7 GB 
per minute. By varying cluster sizes, we find the scaling of our analysis to be sublinear, 
due to a combination of algorithmic limitations and data center response times. The 
cloud-based streaming workflow represents an order-of-magnitude increase in acquisition 
and processing speed compared to a traditional download-store-process workflow, and offers 
the additional benefits of employing a flexible, accessible, and widely used computing 
architecture. It is limited, however, due to its reliance on Internet transfer speeds 
and data center service capacity, and may not work well for repeated analyses or those 
for which even higher data throughputs are needed. These research applications will 
require a new class of cloud-native approaches in which both data and analysis are in the cloud.

#### Metadata

- United States: Seismological Society of America
- Identifier
- ISSN: 0895-0695
- EISSN: 1938-2057
- DOI: 10.1785/0220190357
