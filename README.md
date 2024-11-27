# downloads
This repo serves as a source for the metadata and downloadable files for the [RWSC Research Planning Map](https://rwsc.org/map/). The repo replicates the TOC (folder structure) of the [Research Planning Map](https://rwsc.org/map/). Each service / layer in the Research Planning Map is associated with a metadata (PDF) and a downloadable zipped file in this repo. The zipped file contains the source data as a feature class in a file geodatabase and in KML format. The zipped file also includes the metadata PDF.

Below are the naming rules:
- The base URL is https://rwscollab.github.io/downloads followed by the sub folder name within the TOC.
- The spaces in the sub folder name are replaced with underscores.
- "&" in the sub folder name is replaced with "_and_".

Example:
PAM Deployments under Passive Acoustic Monitoring in the Research Planning Map
Metadata: [https://rwscollab.github.io/downloads/Passive_Acoustic_Monitoring/PAM_Deployments_metadata.pdf](https://rwscollab.github.io/downloads/Passive_Acoustic_Monitoring/PAM_Deployments_metadata.pdf)
Zipped file: [https://rwscollab.github.io/downloads/Passive_Acoustic_Monitoring/PAM_Deployments.zip](https://rwscollab.github.io/downloads/Passive_Acoustic_Monitoring/PAM_Deployments.zip)

## How to prepare metadata and downloadable file
1. Publish a map service to the ArcGIS Server and notify the MGEL Team. The MGEL Team needs to know the service name, layer names within the service and the feature class names linked to the layers.
2. Export the map service metadata as a PDF and upload it to the downloads repo. The metadata has to be placed in the sub folder corresponding to the TOC of the Research Planning Map.
3. Upon the metadata upload, a notification is sent to the MGEL Team.
4. The MGEL Team produces a downloadable zipped file based on the information from Step 1 and upload it to the downloads repo.
