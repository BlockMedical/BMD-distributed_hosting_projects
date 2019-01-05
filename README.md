# BMD Distributed Hosting Projects
The raw sensor data will be stored on public distributed file storage protocols such as IPFS[2] via BlockMed open
source API[3] (See Figure 1). This not only enables other technology and framework such as IoT Fog/Edge computing framework proposed by Cisco[4] to take advantage of IPFS that has better performance than others such as Amazon S3[5], but also shows better performance gain with IPFS[6]. While we have chosen IPFS to start, we are not limited by IPFS, we are also researching other technologies including protocols and actual distributed storages such as BitTorrent, StorJ, Dat, etc.

Read more on our [whitepaper](https://www.slideshare.net/secret/4CGbQSZ5xrHU6w) page 5.

## Distributed Hosting Large Datasets
The mission for these projects are to host big datasets that will benefit pipelines (e.g. ETL, data processing, etc.) and provide a diverse data source for their machine learning and AI projects. We have started by utilizing IPFS and one of the [desktop client Orion](https://github.com/BlockMedical/Orion) to help people onboard and host their big datasets. Onward, these can be expanded to include various technologies to host datasets in a hetrogenous environment.

## Indexing and Full Text Searching on Big Datasets
In order to find the proper datasets for Machine Learning or AI algorithms coming from different domains, we initially selected Elastic Search to index these files registered with BlockMed. However, we are not limited to Elastic Search. The underline technology is based on the public blockchain events and informations with the help of indexing engines, users will find it helpful and easier to navigate through these big datasets hosted on IPFS and other distributed storages.
