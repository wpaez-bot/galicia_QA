# Resumen

**Este repositorio contiene la información y los componentes desarrollados para el proyecto de Banco Galicia, correspondiente al agente `Score AI Ready`, orientado al proceso de control y certificación de activos de datos para su utilización en soluciones de Inteligencia Artificial.**

El proyecto busca establecer un proceso **trazable, gobernado y auditable** para evaluar la calidad e integridad de la evidencia asociada a un activo de datos y determinar su certificación. Para ello, se plantea una arquitectura basada en dos planos: **Evidence Plane**, encargado de la recepción, normalización y almacenamiento de la evidencia, y **Certification Plane**, responsable de la validación, evaluación y generación del score. 

El agente **Score AI Ready** utiliza servicios de **AWS**, incluyendo Amazon S3, AWS Lambda, Step Functions, Amazon Bedrock, Bedrock Guardrails, EventBridge/SQS y CloudWatch/X-Ray, para soportar el flujo de evaluación, gobierno, seguridad, trazabilidad y observabilidad. 

La solución incorpora controles de **Gobierno de Datos, seguridad, trazabilidad y revisión humana (HITL)**. El score final se calcula de manera determinística a partir de una configuración aprobada, mientras que la IA generativa se utiliza para generar juicios estructurados sin delegarle la decisión final de certificación. 

Este repositorio organiza los componentes de código, infraestructura como código, especificaciones, pruebas y documentación necesarios para mantener la trazabilidad entre **requerimientos, diseño, tareas, pruebas, evidencias y gates de aprobación**. 
