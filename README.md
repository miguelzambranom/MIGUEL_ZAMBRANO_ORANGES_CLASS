Dashboard de Emergencias - Clínica San José

Este repositorio contiene el sistema de control y visualización en tiempo real para la gestión del flujo de pacientes en el área de urgencias de la Clínica San José.

Organización del Repositorio

-index.html: Archivo único que contiene la estructura, los estilos de Tailwind CSS y la lógica de funcionamiento.

-README.md: Documentación del proyecto.

Características del Código

Métricas Globales (KPIs): Panel superior con indicadores de Ocupación Total (con desglose de camas), Pacientes en Sala de Espera, Médicos Activos en guardia y Traslados pendientes a UCI.
Tabla de Pacientes Activos: Lista detallada que muestra el ID, nombre, edad, síntomas, tiempo de espera y el nivel de triaje correspondiente a cada paciente.
Filtrado Dinámico: Botones interactivos que permiten segmentar la tabla al instante para ver todos los pacientes o filtrar específicamente por Nivel 1, Nivel 2 o Nivel 3.
Pnel de Alertas: Bloque lateral dedicado a notificaciones urgentes de la dirección médica (como saturación de la UCI o presión en Trauma-Shock).
Simulación en Vivo: Script en JavaScript que actualiza automáticamente las métricas de la sala de espera y la hora de control cada 10 segundos para emular un entorno real.