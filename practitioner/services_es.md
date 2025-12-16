# Servicios de AWS en el Examen Cloud Practitioner

## Servicios de Analítica

**Amazon Athena** - (Serverless) Servicio de consultas interactivas que analiza datos en S3 usando SQL. En el examen, recuerda que es sin servidor, pagas por consulta y es ideal para análisis ad-hoc de data lakes sin infraestructura propia.

**Amazon EMR** - Plataforma administrada para procesamiento de grandes volúmenes de datos con frameworks como Apache Spark y Hadoop. Consejo: EMR aparece en escenarios de big data, análisis de logs o machine learning a gran escala.

**AWS Glue** - (Serverless) Servicio ETL totalmente administrado para preparar e integrar datos. Clave para el examen: Descubre y cataloga datos automáticamente, facilitando la preparación para análisis.

**Amazon Kinesis** - (Serverless) Servicio de streaming de datos en tiempo real para recolectar, procesar y analizar flujos de datos. En el examen: Kinesis es para procesamiento en tiempo real, S3 para procesamiento por lotes.

**Amazon OpenSearch** - Motor administrado de búsqueda y análisis para logs, monitoreo en tiempo real y aplicaciones de búsqueda. Antes llamado Elasticsearch. Úsalo para escenarios de búsqueda y análisis de logs.

**Amazon QuickSight** - (Serverless) Servicio de inteligencia de negocios para crear dashboards y visualizaciones interactivas. En el examen: Relacionado con analítica empresarial y reportes para usuarios no técnicos.

**Amazon Redshift** - Almacén de datos administrado para cargas analíticas. Diferencia clave: Redshift para data warehousing y análisis complejos, RDS para bases de datos transaccionales.

## Integración de Aplicaciones

**Amazon EventBridge** - (Serverless) Servicio de bus de eventos para conectar aplicaciones usando eventos de AWS, SaaS y aplicaciones personalizadas. Consejo: Arquitectura orientada a eventos y bajo acoplamiento.

**Amazon SNS** - (Serverless) Servicio de mensajería pub/sub para enviar notificaciones a múltiples suscriptores. Recuerda: SNS es para fan-out (uno a muchos), SQS es para colas (uno a uno).

**Amazon SQS** - (Serverless) Servicio de colas de mensajes para desacoplar componentes de aplicaciones. Esencial: SQS previene la pérdida de mensajes y permite comunicación asíncrona.

**AWS Step Functions** - (Serverless) Orquestación de flujos de trabajo para coordinar múltiples servicios AWS. En el examen: Para construir aplicaciones complejas de varios pasos con flujos visuales.

## Aplicaciones Empresariales

**Amazon Connect** - Centro de contacto en la nube para operaciones de servicio al cliente. En el examen: Escenarios de call centers, soporte o integración telefónica.

**Amazon SES** - (Serverless) Servicio para envío de emails transaccionales y de marketing. Consejo: SES es para enviar emails programáticamente, no para hosting de correo (eso es WorkMail).

## Gestión de Costos

**AWS Budgets** - Servicio para establecer presupuestos personalizados y alertas de uso/costos. En el examen: Gestión proactiva de costos y notificaciones antes de exceder límites.

**Cost and Usage Reports** - Reportes detallados de facturación y uso. Clave: Información más detallada para análisis y asignación de costos.

**AWS Cost Explorer** - Herramienta para visualizar y gestionar costos de AWS con recomendaciones. Consejo: Ofrece recomendaciones de optimización y ayuda a identificar patrones de gasto.

**AWS Marketplace** - Catálogo digital de soluciones de software que corren en AWS. En el examen: Compra de software de terceros y facturación simplificada.

## Servicios de Cómputo

**AWS Batch** - Servicio administrado para ejecutar cargas de trabajo por lotes. Clave: Provisiona recursos automáticamente para trabajos de procesamiento y análisis de datos.

**Amazon EC2** - Servidores virtuales en la nube, base del cómputo en AWS. Esencial: Tipos de instancia, opciones de compra (On-Demand, Reservadas, Spot) y casos de uso.

**AWS Elastic Beanstalk** - Plataforma como servicio para desplegar aplicaciones web sin gestionar infraestructura. Consejo: Amigable para desarrolladores, gestiona capacidad y balanceo automáticamente.

**Amazon Lightsail** - VPS simplificados con precios predecibles. Clave: Servicio de entrada para cargas simples, incluye cómputo, almacenamiento y red a bajo costo.

**AWS Outposts** - Lleva infraestructura AWS a ubicaciones on-premises. En el examen: Escenarios híbridos donde se requieren servicios AWS en el centro de datos propio.

**Amazon ECR** - Registro administrado de contenedores Docker. Consejo: Almacenamiento de imágenes de contenedores e integración con ECS/EKS.

**Amazon ECS** - Orquestación administrada de contenedores Docker. Clave: Servicio totalmente administrado, se integra con otros servicios AWS.

**Amazon EKS** - Servicio administrado de Kubernetes. En el examen: Cuando se requiere compatibilidad o experiencia con Kubernetes.

**AWS Fargate** - (Serverless) Motor de cómputo para contenedores sin gestionar servidores. Clave: Contenedores sin servidor, solo lanzas los contenedores.

**AWS Lambda** - (Serverless) Ejecuta código sin aprovisionar servidores, cómputo orientado a eventos. Esencial: Pagas solo por tiempo de ejecución, escala automáticamente, ideal para arquitecturas event-driven.

## Servicios de Base de Datos

**Amazon Aurora** - Base de datos relacional de alto rendimiento compatible con MySQL y PostgreSQL. Consejo: Aurora Serverless para cargas variables, Aurora estándar para alto rendimiento constante.

**Amazon DocumentDB** - Base de datos de documentos compatible con MongoDB. Clave: Para almacenamiento de documentos, datos JSON o compatibilidad MongoDB.

**Amazon DynamoDB** - (Serverless) Base de datos NoSQL rápida y flexible con baja latencia. Esencial: Totalmente administrada, escala automáticamente, ideal para aplicaciones web y móviles.

**Amazon ElastiCache** - Servicio de caché en memoria compatible con Redis y Memcached. En el examen: Mejora el rendimiento de aplicaciones almacenando datos frecuentemente accedidos.

**Amazon Neptune** - Base de datos de grafos administrada para aplicaciones con datos altamente conectados. Clave: Redes sociales, detección de fraude, motores de recomendación.

**Amazon RDS** - Servicio administrado de bases de datos relacionales (MySQL, PostgreSQL, Oracle, SQL Server, MariaDB). Enfoque: Backups automáticos, parches y alta disponibilidad Multi-AZ.

## Herramientas de Desarrollo

**AWS CLI** - Interfaz de línea de comandos para interactuar con servicios AWS. Consejo: Alternativa a la consola para automatización y scripting.

**AWS CodeBuild** - (Serverless) Servicio administrado de compilación y pruebas de código. Clave: Parte de CI/CD, escala automáticamente, pagas solo por tiempo de build.

**AWS CodePipeline** - Servicio CI/CD administrado para automatizar pipelines de entrega. En el examen: Entrega automatizada desde código fuente hasta producción.

**AWS X-Ray** - Servicio de trazabilidad distribuida para depurar y analizar aplicaciones de microservicios. Consejo: Identifica cuellos de botella y flujos de solicitudes.

## Computación para Usuarios Finales

**Amazon AppStream 2.0** - Servicio administrado de streaming de aplicaciones de escritorio. En el examen: Acceso a aplicaciones desde cualquier dispositivo sin instalación.

**Amazon WorkSpaces** - Escritorios virtuales como servicio. Clave: Infraestructura VDI en la nube para trabajo remoto.

**Amazon WorkSpaces Secure Browser** - Servicio administrado de navegador web seguro. Consejo: Para escenarios que requieren navegación web aislada por cumplimiento.

## Web y Móvil Frontend

**AWS Amplify** - Plataforma para construir aplicaciones web y móviles full-stack con CI/CD integrado. Enfoque: Plataforma amigable para desarrolladores frontend.

**AWS AppSync** - (Serverless) Servicio administrado de API GraphQL para sincronización de datos en tiempo real. Clave: APIs en tiempo real, sincronización offline y casos de uso GraphQL.

## Internet de las Cosas

**AWS IoT Core** - Servicio administrado para conectar dispositivos IoT a AWS. En el examen: Escenarios con sensores, dispositivos inteligentes o despliegues IoT a gran escala.

## Machine Learning

**Amazon Comprehend** - (Serverless) Servicio de procesamiento de lenguaje natural para análisis de texto. Consejo: Extrae insights, análisis de sentimiento y entidades sin experiencia en ML.

**Amazon Kendra** - Servicio de búsqueda inteligente potenciado por machine learning. Clave: Búsqueda empresarial en documentos y fuentes de datos usando lenguaje natural.

**Amazon Lex** - (Serverless) Servicio para crear chatbots y aplicaciones de voz. En el examen: Escenarios de IA conversacional, chatbots o interfaces de voz.

**Amazon Polly** - (Serverless) Servicio de texto a voz para convertir texto en habla realista. Consejo: Creación de contenido de audio, accesibilidad o aplicaciones de voz.

**Amazon Q** - Asistente con IA de AWS que ayuda con código, resolución de problemas y buenas prácticas. Clave: Asistente inteligente de AWS para productividad y guía.

**Amazon Rekognition** - (Serverless) Servicio de visión computacional para análisis de imágenes y videos. Enfoque: Reconocimiento facial, detección de objetos y moderación de contenido.

**Amazon SageMaker** - Plataforma administrada de machine learning para construir, entrenar y desplegar modelos ML. En el examen: Cuando se requiere desarrollo y despliegue de modelos personalizados.

**Amazon Textract** - (Serverless) Servicio para extraer texto y datos de documentos usando OCR y ML. Clave: Convertir documentos escaneados en texto y datos estructurados.

**Amazon Transcribe** - (Serverless) Servicio de transcripción de voz a texto. Consejo: Transcripción de reuniones, análisis de voz o creación de subtítulos.

**Amazon Translate** - (Serverless) Servicio de traducción de texto en tiempo real. En el examen: Aplicaciones multilingües o localización de contenido.

## Gestión y Gobierno

**AWS Auto Scaling** - Servicio que ajusta automáticamente la capacidad de cómputo según la demanda. Esencial: Mantiene disponibilidad y optimiza costos escalando recursos.

**AWS CloudFormation** - Infraestructura como código para aprovisionar recursos AWS con plantillas. Consejo: Gestión declarativa de infraestructura, despliegues repetibles.

**AWS CloudTrail** - Servicio que registra llamadas API y actividad de cuentas para auditoría y cumplimiento. Clave: Monitoreo de seguridad, cumplimiento y trazabilidad de acciones.

**Amazon CloudWatch** - Monitoreo y observabilidad de recursos y aplicaciones AWS. Esencial: Recopila métricas, logs y eventos; permite alarmas y respuestas automáticas.

**AWS Compute Optimizer** - Recomienda recursos óptimos de cómputo según uso. Enfoque: Optimización de costos mediante recomendaciones de dimensionamiento.

**AWS Config** - Rastrea configuraciones de recursos y cumplimiento con estándares organizacionales. Clave: Gestión de configuración, monitoreo de cumplimiento y cambios.

**AWS Control Tower** - Configura y gestiona entornos multi-cuenta seguros y conformes. En el examen: Gobierno empresarial y configuración automatizada con buenas prácticas.

**AWS Health Dashboard** - Proporciona alertas y guía cuando eventos AWS afectan tus recursos. Consejo: Notificación proactiva sobre problemas de servicios AWS.

**AWS License Manager** - Gestiona licencias de software en AWS y on-premises. Clave: Cumplimiento y optimización de licencias comerciales.

**AWS Management Console** - Interfaz web para acceder y gestionar servicios AWS. Básico: Principal forma de interactuar con AWS gráficamente.

**AWS Organizations** - Gestión centralizada de múltiples cuentas AWS con facturación consolidada. Esencial: Gestión multi-cuenta, unidades organizativas y políticas de control de servicios.

**AWS Service Catalog** - Crea y gestiona catálogos de servicios y recursos aprobados. En el examen: Estandarización de despliegues y gobierno en empresas.

**AWS Service Quotas** - Visualiza y gestiona límites de servicios. Clave: Entender y solicitar aumentos de límites predeterminados.

**AWS Systems Manager** - Interfaz unificada para gestionar recursos AWS con automatización. Consejo: Gestión de parches, configuración y operaciones.

**AWS Trusted Advisor** - Proporciona recomendaciones en tiempo real para optimizar infraestructura. Esencial: Cinco categorías: costos, seguridad, tolerancia a fallos, rendimiento y límites de servicio.

**AWS Well-Architected Tool** - Revisa cargas de trabajo según buenas prácticas de arquitectura AWS. Clave: Implementa los pilares del Well-Architected Framework.

## Migración y Transferencia

**AWS Application Discovery Service** - Ayuda a planificar migraciones descubriendo aplicaciones y dependencias on-premises. En el examen: Primer paso para entender infraestructura actual.

**AWS Application Migration Service** - Migra aplicaciones a AWS con mínimo downtime. Clave: Migraciones lift-and-shift desde on-premises u otras nubes.

**AWS Database Migration Service** - Migra bases de datos a AWS con mínimo downtime. Consejo: Soporta migraciones homogéneas y heterogéneas, incluyendo replicación continua.

**Migration Evaluator** - Crea casos de negocio para migración a la nube según infraestructura actual. En el examen: Herramienta de análisis de costos y planificación.

**AWS Migration Hub** - Ubicación central para monitorear el progreso de migraciones. Clave: Vista unificada para proyectos de migración.

**AWS Schema Conversion Tool** - Convierte esquemas de bases de datos entre motores. Enfoque: Parte del proceso de migración cuando se cambia de motor.

**AWS Snow Family** - Dispositivos físicos para transferir grandes volúmenes de datos a/desde AWS. Esencial: Snowcone (8TB), Snowball Edge (hasta 80TB), Snowmobile (hasta 100PB) según el volumen.

## Redes y Entrega de Contenido

**Amazon API Gateway** - (Serverless) Servicio administrado para crear, desplegar y gestionar APIs. Consejo: Puerta de entrada para aplicaciones, maneja autenticación, limitación y monitoreo.

**Amazon CloudFront** - (Serverless) CDN global para entrega rápida de contenido. Esencial: Cachea contenido en ubicaciones edge para mejor rendimiento y menor latencia.

**AWS Direct Connect** - Conexión de red dedicada entre tus instalaciones y AWS. Clave: Rendimiento consistente, menor costo de ancho de banda y mayor seguridad.

**AWS Global Accelerator** - (Serverless) Mejora el rendimiento global de aplicaciones usando la red de AWS. En el examen: Mejor que CloudFront para tráfico no HTTP y aplicaciones en tiempo real.

**AWS PrivateLink** - Acceso privado a servicios AWS sin gateway de internet. Consejo: Conectividad segura y privada entre VPCs y servicios AWS o de terceros.

**Amazon Route 53** - (Serverless) Servicio DNS escalable para registro y enrutamiento de dominios. Esencial: DNS con chequeos de salud y políticas de enrutamiento para alta disponibilidad.

**AWS Transit Gateway** - Conecta VPCs y redes on-premises a través de un hub central. Clave: Simplifica la arquitectura de red evitando peering complejo.

**Amazon VPC** - Nube privada virtual para lanzar recursos AWS en una red aislada. Fundamental: Base de redes en AWS, incluye subredes, grupos de seguridad y NACLs.

**AWS VPN** - Conexión segura entre tu red y VPCs de AWS. En el examen: Dos tipos - Site-to-Site VPN para oficinas y Client VPN para usuarios individuales.

## Seguridad, Identidad y Cumplimiento

**AWS Artifact** - (Serverless) Portal para acceder a documentación y acuerdos de cumplimiento de AWS. Consejo: Descarga reportes SOC, PCI y otras certificaciones.

**AWS Audit Manager** - Automatiza la preparación de auditorías y monitoreo de cumplimiento. Clave: Simplifica auditorías recolectando evidencia automáticamente.

**AWS Certificate Manager** - (Serverless) Provisión y gestión de certificados SSL/TLS. En el examen: Certificados gratuitos para servicios AWS, renovación automática y gestión simplificada.

**AWS CloudHSM** - Módulos de seguridad hardware en la nube para gestión de claves. Enfoque: Hardware dedicado para operaciones criptográficas cuando se requiere cumplimiento regulatorio.

**Amazon Cognito** - (Serverless) Autenticación y autorización de usuarios en apps web y móviles. Consejo: User pools para autenticación, identity pools para autorización, soporta proveedores sociales.

**Amazon Detective** - Analiza y visualiza datos de seguridad para investigar problemas. Clave: Usa machine learning para identificar causas raíz de hallazgos de seguridad.

**AWS Directory Service** - Active Directory administrado en la nube AWS. En el examen: Integración con Active Directory on-premises.

**AWS Firewall Manager** - Configura y gestiona reglas de firewall centralizadamente. Consejo: Simplifica la gestión de seguridad en múltiples cuentas y aplicaciones.

**Amazon GuardDuty** - (Serverless) Detección inteligente de amenazas usando machine learning. Esencial: Monitoreo continuo, detecta actividad maliciosa y comportamientos no autorizados.

**AWS IAM** - Gestión de identidades y accesos para controlar acceso a servicios y recursos AWS. Fundamental: Usuarios, grupos, roles, políticas - base de la seguridad en AWS.

**AWS IAM Identity Center** - Gestión centralizada de acceso para múltiples cuentas y aplicaciones. Clave: Single sign-on (SSO) y permisos centralizados en AWS Organizations.

**Amazon Inspector** - Evaluación automática de seguridad para aplicaciones e infraestructura. En el examen: Evaluaciones de vulnerabilidad, pruebas de seguridad y cumplimiento.

**AWS KMS** - (Serverless) Servicio de gestión de claves para crear y administrar claves de cifrado. Esencial: Claves administradas por el cliente, cifrado en sobre e integración con otros servicios AWS.

**Amazon Macie** - (Serverless) Seguridad de datos usando ML para descubrir y proteger datos sensibles. Consejo: Clasifica y protege automáticamente datos sensibles como PII en S3.

**AWS RAM** - (Serverless) Resource Access Manager para compartir recursos AWS entre cuentas. Clave: Simplifica el compartir recursos en entornos multi-cuenta.

**AWS Secrets Manager** - (Serverless) Almacena y gestiona información sensible como contraseñas y claves API. En el examen: Rotación automática y almacenamiento seguro de credenciales.

**AWS Security Hub** - Gestión centralizada de hallazgos de seguridad. Consejo: Panel único para postura de seguridad, integra servicios AWS y herramientas de terceros.

**AWS Shield** - (Serverless) Protección DDoS para aplicaciones AWS. Esencial: Shield Standard (gratis, protección básica) vs Shield Advanced (pago, protección mejorada y soporte 24/7).

**AWS WAF** - (Serverless) Firewall de aplicaciones web para proteger contra ataques comunes. Clave: Protege contra inyección SQL, XSS y otros ataques web.

## Servicios de Almacenamiento

**AWS Backup** - (Serverless) Servicio centralizado de backups con políticas automatizadas. Consejo: Backup cross-region, cumplimiento y gestión centralizada de backups.

**Amazon EBS** - Discos duros. Almacenamiento en bloques persistente para instancias EC2. Esencial: Tipos de volumen, snapshots y opciones de cifrado.

**Amazon EFS** - (Serverless) Sistema de archivos NFS administrado para EC2 con escalado automático. Clave: Almacenamiento compartido para instancias EC2, enfocado en Linux.

**AWS Elastic Disaster Recovery** - Recuperación rápida de servidores físicos, virtuales y en la nube. En el examen: Solución de recuperación ante desastres con protección continua y recuperación rápida.

**Amazon FSx** - Sistemas de archivos administrados optimizados para casos de uso específicos (Windows, Lustre, NetApp, OpenZFS). Consejo: Sistemas de alto rendimiento para cargas especializadas, popular en Windows.

**Amazon S3** - (Serverless) Almacenamiento de objetos para guardar y recuperar cualquier cantidad de datos. Fundamental: Clases de almacenamiento, políticas de ciclo de vida, versionado y casos de uso.

**S3 Glacier** - (Serverless) Almacenamiento de archivo a largo plazo con opciones de recuperación de minutos a horas. Clave: Diferentes velocidades y costos de recuperación.

**AWS Storage Gateway** - Almacenamiento híbrido conectando on-premises con AWS. En el examen: Tres tipos - File, Volume y Tape Gateway para necesidades híbridas.

## Soporte

**AWS Support** - Servicio de soporte técnico con diferentes planes (Básico, Developer, Business, Enterprise). Esencial: Entender qué incluye cada plan, tiempos de respuesta y cuándo recomendar cada uno.
