<h1 align="center">Raúl Pravia</h1>

<p align="center">
  <a href="https://github.com/Rpravia042">English</a> · <strong>Español</strong>
</p>

<p align="center">
  <img src="tomassa-banner.png" alt="Tomassa, una gata naranja y blanca acurrucada sobre un fondo crema" width="900">
</p>

<p align="center">Infraestructura en la nube · Observabilidad · Análisis de logs de seguridad</p>

<p align="center">
  <img src="assets/orbit-divider.gif" width="720" height="10" alt="">
</p>

## Sobre mí

Hago proyectos prácticos de infraestructura en la nube y observabilidad. Me gusta investigar cómo fallan los sistemas y documentar cómo comprobé que la solución funcionó.

<details>
<summary>Cómo trabajo</summary>

```yaml
enfoque:
  - seguir la señal desde la recolección hasta la búsqueda
  - reproducir el problema y verificar la solución
  - documentar la evidencia y sus límites
```

</details>

## Herramientas

**Nube y sistemas**  
![Google Cloud](assets/badges/google-cloud.svg) ![Linux](assets/badges/linux.svg)

**Observabilidad**  
![Splunk Enterprise](assets/badges/splunk.svg) ![SPL](assets/badges/spl.svg) ![Cloud Monitoring](assets/badges/cloud-monitoring.svg) ![Ops Agent](assets/badges/ops-agent.svg)

**Scripting y validación**  
![Bash](assets/badges/bash.svg) ![Python](assets/badges/python.svg) ![Git](assets/badges/git.svg) ![GitHub](assets/badges/github.svg)

<p align="center">
  <img src="assets/orbit-divider.gif" width="720" height="10" alt="">
</p>

## Proyectos

### [Splunk Distributed Lab](https://github.com/Rpravia042/splunk-distributed-lab)

Monté un laboratorio de Splunk de tres nodos en Google Cloud y seguí la telemetría de Linux desde la recolección hasta la búsqueda distribuida. Cuando el Search Head se quedó con poco espacio en disco, amplié su sistema de archivos, comprobé que las búsquedas volvieran a funcionar y probé dos alertas independientes en Cloud Monitoring.

| 3 nodos | 2 alertas externas | 22 pruebas del repositorio |
| --- | --- | --- |
| Universal Forwarder, Indexer y Search Head | Poco espacio y ausencia de métricas de disco | Comprobaciones de recuperación, sanitización y monitoreo |

[Arquitectura](https://github.com/Rpravia042/splunk-distributed-lab#architecture) · [Caso de recuperación de disco](https://github.com/Rpravia042/splunk-distributed-lab#disk-capacity-case-study) · [Validación de alertas](https://github.com/Rpravia042/splunk-distributed-lab/blob/main/configs/examples/observability-v2/cloud-monitoring/README.md#observed-validation) · [Guía del lab en español](https://github.com/Rpravia042/splunk-distributed-lab/blob/main/docs/guia-es.md)

<details>
<summary>En desarrollo</summary>

- **TomaNotas** — una aplicación para tomar notas.
- **Analizador en Python** — una herramienta de análisis escrita en Python.

</details>
