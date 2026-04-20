# Calculadora-Distribuida

Descripción

La calculadora distribuida es una aplicación de cálculo distribuido diseñada para el procesamiento eficiente de operaciones sobre grandes volúmenes de datos, mediante el uso de múltiples computadoras interconectadas a un servidor central.

El sistema implementa un enfoque de delegación de tareas, donde los clientes envían solicitudes de cálculo al servidor, el cual se encarga de gestionar y distribuir la carga de trabajo de manera eficiente. Este modelo permite optimizar el uso de recursos computacionales y reducir los tiempos de procesamiento.

 Características Principales
Conectividad en red bajo un modelo cliente-servidor
Procesamiento de datos a gran escala
Distribución eficiente de tareas de cálculo
Ejecución remota de operaciones desde múltiples clientes
Escalabilidad mediante la incorporación de nuevos nodos al sistema
 Arquitectura del Sistema

El sistema se basa en una arquitectura Cliente-Servidor, compuesta por los siguientes elementos:

Servidor
Recepción y gestión de solicitudes de cálculo
Administración de múltiples conexiones concurrentes
Distribución de tareas entre los clientes disponibles
Procesamiento y retorno de resultados
Cliente
Envío de operaciones al servidor
Ejecución de tareas asignadas 
Presentación de resultados al usuario final
 Tecnologías Utilizadas
Lenguaje de programación: Java
Comunicación: Sockets
Manejo de datos: (XML, JSON)
Arquitectura: Cliente-Servidor
