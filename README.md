<h1 align="center">Raúl Pravia</h1>

<p align="center">
  <strong>English</strong> · <a href="https://github.com/Rpravia042/Rpravia042/blob/main/README.es.md">Español</a>
</p>

<p align="center">
  <img src="tomassa-banner.png" alt="Tomassa, an orange-and-white cat curled up against a cream background" width="900">
</p>

<p align="center">Cloud infrastructure · Observability · Security log analysis</p>

<p align="center">
  <img src="assets/orbit-divider.gif" width="720" height="10" alt="">
</p>

## About me

I've used Microsoft Azure and Google Cloud in my projects. I like using Linux logs and metrics to figure out why systems fail. In my Splunk lab, I set up distributed search and tested two disk monitoring alerts that work independently of Splunk.

## Tech stack

**Cloud & systems**  
![Google Cloud](assets/badges/google-cloud.svg) ![Microsoft Azure](assets/badges/azure.svg) ![Linux](assets/badges/linux.svg)

**Observability**  
![Splunk Enterprise](assets/badges/splunk.svg) ![SPL](assets/badges/spl.svg) ![Cloud Monitoring](assets/badges/cloud-monitoring.svg) ![Ops Agent](assets/badges/ops-agent.svg)

**Scripting & validation**  
![Bash](assets/badges/bash.svg) ![Python](assets/badges/python.svg) ![Git](assets/badges/git.svg) ![GitHub](assets/badges/github.svg)

<p align="center">
  <img src="assets/orbit-divider.gif" width="720" height="10" alt="">
</p>

## Projects

### [Splunk Distributed Lab](https://github.com/Rpravia042/splunk-distributed-lab)

I built a three-node Splunk lab on Google Cloud and traced Linux telemetry from collection to distributed search. When the Search Head ran low on disk space, I expanded its filesystem, verified that searches worked again, and tested two independent Cloud Monitoring alerts.

| 3 nodes | 2 external alerts | 22 repository tests |
| --- | --- | --- |
| Universal Forwarder, Indexer and Search Head | Low space and missing disk metrics | Recovery, sanitization and monitoring checks |

[Architecture](https://github.com/Rpravia042/splunk-distributed-lab#architecture) · [Disk recovery case study](https://github.com/Rpravia042/splunk-distributed-lab#disk-capacity-case-study) · [Alert validation](https://github.com/Rpravia042/splunk-distributed-lab/blob/main/configs/examples/observability-v2/cloud-monitoring/README.md#observed-validation)

<details>
<summary>In development</summary>

- **TomaNotas** — a note-taking app.
- **Python analyzer** — an analysis tool written in Python.

</details>
