# Dashboard-Power-BI-Tickets-de-Mesa-de-Ayuda-TI

El objetivo es crear un Dashboard automático en Power BI que sea utilizado por un coordinador del área de TI, y que también pueda aprovecharlo un técnico o auxiliar del área para darle seguimiento tanto a la carga de trabajo cómo al estado de los requerimientos dados por Tickets.

El dashboard es un mínimo producto viable, esta sujeto a mejoras.

Para esta versión del informe se ha tomado la decisión de eliminar los IDs de los tickets que estén duplicados, ya que se observó que para un mismo caso habia duplicidad tanto en fechas como en el ID, es por eso que hay menos datos observados  en el Dashboard frente al total que se puede ver en la fuente de datos. Se le dió prioridad a los datos únicos y no dejar duplicados.

## Acceso al Dashboard ❕
Click en el siguiente enlace para acceder al dashboard interactivo (se recomienda abrir el enlace en otra pestaña):

[Dashboard: Tickets Mesa de Ayuda](https://app.powerbi.com/view?r=eyJrIjoiMjMxYWYxZTgtNjJmNi00MmZhLWI4NzMtNTMzNmQzMmNkMDRhIiwidCI6Ijk5ZTFlNzIxLTcxODQtNDk4ZS04YWZmLWIyYWQ0ZTUzYzFjMiIsImMiOjR9)

## 📊 Fuente de los datos
Nombre del Dataset: Registro de Tickets de Mesa de Ayuda – Servicios de Tecnología de la Información

- El método de exportación ha sido a través de la API de DatosGov en formato JSON
- Se ha establecido una actualización programada de carácter semanal en caso de que ingresen nuevos registros al set de datos. El d  Dashboard se actualiza automáticamente cada domingo a la 1 am.


https://www.datos.gov.co/Educaci-n/Registro-de-Tickets-de-Mesa-de-Ayuda-Servicios-de-/iupi-ay2g/about_data

  Nota: Es preferible copiar el link anterior  y pegarlo en una pestaña nueva.

<img width="1595" height="214" alt="image" src="https://github.com/user-attachments/assets/1fda81f5-2f3b-4a59-872d-c180109f9502" />


<img width="1129" height="767" alt="image" src="https://github.com/user-attachments/assets/c264bc5a-d163-4d9b-8efc-5148ee1fca25" />


## 📈 Vistazo al Dashboard

Página 1: Desempeño Tickets
---
<img width="1296" height="675" alt="image" src="https://github.com/user-attachments/assets/edfad299-5596-4daa-bcdc-e3f4641f1fbc" />

Página 2: Seguimiento de Técnicos TI
--
<img width="1289" height="678" alt="image" src="https://github.com/user-attachments/assets/4080babf-2b36-4856-ae87-2b4dab7806cc" />


