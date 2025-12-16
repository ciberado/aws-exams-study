# Conceptos de AWS Practitioner

## Fundamentos de la Nube

### **Valor de la Nube**
Comprender los **beneficios empresariales** de migrar a la nube: **reducción de costos**, **mayor agilidad**, **escalabilidad global** y **aceleración de la innovación**.

### **Modelo de Responsabilidad Compartida**
AWS gestiona la **seguridad de la infraestructura** (física, red, hipervisor) mientras que los clientes se encargan de la **seguridad en la nube** (datos, aplicaciones, SO, configuración de red).

### **Marco Well-Architected**
Seis pilares para construir sistemas **confiables**, **seguros** y **eficientes**: **Excelencia Operacional**, **Seguridad**, **Confiabilidad**, **Eficiencia de Rendimiento**, **Optimización de Costos** y **Sostenibilidad**.

#### **Excelencia Operacional**
Capacidad para soportar el desarrollo y operación de cargas de trabajo, obtener visibilidad y mejorar procesos continuamente.

#### **Seguridad**
Capacidad para proteger datos, sistemas y activos aprovechando tecnologías en la nube para mejorar la seguridad.

#### **Confiabilidad**
Capacidad de una carga de trabajo para funcionar correctamente y de forma consistente cuando se espera.

#### **Eficiencia de Rendimiento**
Uso eficiente de recursos de cómputo para cumplir requisitos y mantener eficiencia ante cambios de demanda y tecnología.

#### **Optimización de Costos**
Capacidad de operar sistemas para entregar valor al menor costo posible.

#### **Sostenibilidad**
Mejora continua del impacto ambiental reduciendo consumo energético y aumentando eficiencia.

### **Modelos de Despliegue**
**Nube pública** (multiusuario), **nube privada** (dedicada), **nube híbrida** (combinada) y **infraestructura local**.

### **Economía de la Nube**
Comprender **CapEx vs OpEx**, **economías de escala**, **pago por uso** y **costo total de propiedad** (TCO).

## Migración y Adopción de la Nube

### **Migración a la Nube**
Estrategias para mover cargas de trabajo: **rehost** (lift-and-shift), **replataformar**, **refactorizar**, **retirar**, **retener** y **recomprar**.

### **Marco de Adopción de la Nube (CAF)**
Metodología AWS con seis **perspectivas** y cuatro **fases** para una transformación exitosa. Las perspectivas representan capacidades organizacionales y las fases el avance en madurez.

#### **Perspectivas CAF**
Capacidades organizacionales a abordar durante la adopción:

##### **Perspectiva de Negocio**
Alinea inversiones en la nube con resultados empresariales, valor, ROI y gestión de riesgos.

##### **Perspectiva de Personas**
Gestión del cambio, capacitación y desarrollo de habilidades.

##### **Perspectiva de Gobernanza**
Marcos para gestionar entornos en la nube: portafolio, métricas, licencias.

##### **Perspectiva de Plataforma**
Arquitectura técnica e implementación: infraestructura, aplicaciones, datos y aprovisionamiento.

##### **Perspectiva de Seguridad**
Confidencialidad, integridad y disponibilidad de datos y cargas de trabajo.

##### **Perspectiva de Operaciones**
Gestión de servicios en la nube: observabilidad, eventos e incidentes.

#### **Fases CAF**
Etapas de madurez en adopción:

##### **Fase de Visualización**
Demuestra valor y estrategia mediante alineación de partes interesadas y casos de negocio.

##### **Fase de Alineación**
Identifica brechas y dependencias para crear planes de acción y desarrollo de habilidades.

##### **Fase de Lanzamiento**
Pilotos en producción para demostrar valor incremental y validar el enfoque.

##### **Fase de Escalado**
Expande pilotos para lograr resultados empresariales y transformación organizacional.

### **Herramientas y Métodos de Migración**
**AWS Migration Hub**, **Database Migration Service** y herramientas de evaluación para planificar y ejecutar migraciones.

## Seguridad y Cumplimiento

### **Mejores Prácticas de Seguridad**
Implementar **defensa en profundidad**, **mínimos privilegios**, **cifrado de datos** y **monitoreo continuo**.

### **Gestión de Identidad**
**AWS IAM** para control de acceso, **MFA**, **acceso basado en roles** e **identidad federada**.

### **Métodos de Autenticación**
**Usuario/contraseña**, **claves de acceso**, **credenciales temporales**, **SAML**, **OpenID Connect** y **AWS SSO**.

### **Almacenamiento de Credenciales**
Uso seguro de **Secrets Manager**, **Parameter Store** y **roles IAM** en vez de credenciales codificadas.

### **Protección del Usuario Root**
Asegurar la **cuenta root** con **contraseñas fuertes**, **MFA**, **uso limitado** y **eliminación de claves**.

### **Opciones de Cifrado**
**Cifrado en reposo** y **en tránsito** con **KMS**, **CloudHSM**, **SSL/TLS** y cifrado específico por servicio.

### **Cumplimiento y Gobernanza**
Cumplir **requisitos regulatorios** mediante **programas de cumplimiento AWS**, **auditorías**, **residencia de datos** y marcos de gobernanza.

### **Registro y Monitoreo**
**CloudTrail** para logs de API, **CloudWatch** para métricas y monitoreo, y **Config** para cumplimiento de configuración.

## Arquitectura y Disponibilidad

### **Alta Disponibilidad**
Diseño en **múltiples zonas de disponibilidad** con **redundancia**, **mecanismos de failover** y **balanceo de carga**.

### **Recuperación ante Desastres**
Planificación **RTO/RPO** usando **backups**, **replicación entre regiones** y **recuperación automatizada**.

### **Continuidad del Negocio**
Garantizar **operaciones ininterrumpidas** mediante **tolerancia a fallos**, **backups** y **respuesta a incidentes**.

### **Elasticidad y Agilidad**
**Autoescalado** para manejar **demanda variable**, **provisión rápida** y **optimización de recursos**.

### **Balanceo de Carga**
Distribución de tráfico entre **instancias** usando **Application Load Balancer**, **Network Load Balancer** y **Classic Load Balancer**.

### **Autoescalado**
**Escalado horizontal** según **patrones de demanda**, **métricas** y **escalado predictivo**.

## Infraestructura y Aprovisionamiento

### **Métodos de Aprovisionamiento**
**Consola AWS**, **CLI**, **SDKs**, **CloudFormation**, **CDK** y herramientas de terceros para desplegar recursos.

### **Infraestructura como Código**
**CloudFormation**, **CDK** y **Terraform** para despliegues **versionados** y **repetibles**.

### **Beneficios de la Automatización**
**Menos errores humanos**, **despliegues consistentes**, **provisión rápida** y **optimización de costos**.

## Redes y Conectividad

### **Seguridad de Red**
Diseño de **VPC**, **grupos de seguridad**, **NACLs**, **WAF**, **Shield** y segmentación de red.

### **Opciones de Conectividad**
**VPN**, **Direct Connect**, **Transit Gateway**, **VPC Peering** y **PrivateLink** para conectividad segura.

### **Soberanía de Datos**
Comprender **ubicación de datos**, **cumplimiento regional**, **transferencia internacional** y **residencia local**.

## Almacenamiento y Respaldo

### **Clases de Almacenamiento**
**S3** (Standard, IA, Glacier, Deep Archive), **EBS**, **EFS** para diferentes **rendimientos** y **costos**.

### **Políticas de Ciclo de Vida**
Transición automática de datos entre clases según **patrones de acceso** y **retención**.

### **Casos de Uso de Backup**
**Recuperación puntual**, **backup entre regiones**, **programación automática** y **recuperación ante desastres**.

### **Intelligent Tiering**
**S3 Intelligent Tiering** mueve objetos entre **acceso frecuente** e **infrecuente** según uso para optimizar costos.

## Gestión de Costos

### **Optimización de Costos**
**Ajuste de tamaño**, **instancias reservadas**, **spot**, **optimización de almacenamiento** y **programación de recursos**.

### **Costos Fijos vs Variables**
Diferencias entre **on-demand**, **reservadas**, **descuentos por compromiso** y beneficios de costos variables.

### **Ajuste de Tamaño**
Alinear **tipos y tamaños de instancias** a la **carga real** para mejor relación **precio-rendimiento**.

### **Modelos de Precios**
**On-demand**, **reservadas**, **spot**, **savings plans** y **dedicated hosts**.

### **Niveles y Costos de Almacenamiento**
Precios de **S3**, **costos de recuperación** y **transferencia de datos**.

### **Costos de Transferencia de Datos**
**Entrante** (generalmente gratis), **saliente**, **entre regiones** y optimización con **CDN**.

### **Etiquetas de Asignación de Costos**
**Etiquetado de recursos** para **seguimiento de costos**, **facturación por departamento** y **gestión de presupuestos**.

## Soporte y Monitoreo

### **Soporte de Facturación**
**Cost Explorer**, **presupuestos y alertas**, **reportes de facturación** y **detección de anomalías**.

### **Planes de Soporte**
**Básico** (gratis), **Developer**, **Business**, **Enterprise** con diferentes **tiempos de respuesta** y **cobertura**.

### **Red de Socios AWS**
**Socios de consultoría**, **tecnología**, **proveedores de soluciones** y **capacitación**.

### **Trusted Advisor**
**Recomendaciones de buenas prácticas** para **costos**, **seguridad**, **tolerancia a fallos**, **rendimiento** y **límites de servicio**.

### **Panel de Salud**
**Monitoreo de servicios**, **notificaciones personales** y **mantenimiento programado**.

### **Reporte de Abusos**
Proceso para reportar **incidentes de seguridad**, **actividad sospechosa** y **violaciones de políticas**.

### **Asistencia Técnica**
**Documentación**, **foros**, **casos de soporte**, **guía arquitectónica** y **recursos de solución de problemas**.

## Servicios por Función

### **Tareas de IA/ML**
**SageMaker** para aprendizaje automático, **Rekognition** para imágenes, **Comprehend** para texto y **Lex** para chatbots.

### **Tareas de Analítica**
**Redshift** para data warehousing, **EMR** para big data, **Kinesis** para streaming y **QuickSight** para visualización.

### **Integración de Aplicaciones**
**SQS** para colas, **SNS** para notificaciones, **Step Functions** para flujos y **EventBridge** para eventos.

### **Aplicaciones Empresariales**
**WorkMail** para correo, **Chime** para comunicación, **WorkDocs** para colaboración y **Connect** para centros de contacto.

### **Herramientas de Desarrollador**
**CodeCommit**, **CodeBuild**, **CodeDeploy**, **CodePipeline** para **CI/CD** y **Cloud9** para desarrollo.

### **Computación para Usuarios Finales**
**WorkSpaces** para escritorios virtuales, **AppStream** para streaming de aplicaciones y **WorkLink** para acceso móvil seguro.

### **Servicios Frontend**
**CloudFront** para entrega de contenido, **Route 53** para DNS, **API Gateway** para APIs y **Amplify** para aplicaciones web.

### **Gestión de IoT**
**IoT Core** para conectividad de dispositivos, **IoT Device Management**, **IoT Analytics** y **IoT Greengrass** para edge computing.
