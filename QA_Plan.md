ID	Caso de Prueba	Datos de Entrada	Resultado Esperado	Estado
CP01	Inicio de sesión 	RUT: 12.345.678-9, Pass: 1234 	Ingreso exitoso al Dashboard correspondiente. 	Exitoso 
CP02	Visualizar saldo 	Carga de perfil de usuario 	Despliegue correcto de Saldo, Meta y % avance. 	Exitoso 
CP03	Calcular pendiente 	Meta: $1.200.000, Acumulado: $720.000 	Cálculo automático de Saldo Pendiente: $480.000. 	Exitoso 
CP04	Descargar contrato 	Clic en "Descargar Contrato" 	Generación y descarga de archivo PDF verificado. 	Exitoso 
CP05	Descargar póliza 	Clic en "Descargar Póliza" 	Descarga de PDF con cobertura técnica de seguro. 	Exitoso 
CP06	Registro contrato 	Curso: 4to Medio A, Destino: Brasil 	Persistencia de datos y mensaje de éxito visual. 	Exitoso 
CP07	Consulta depósitos 	Selección "Colegio San Juan" 	Sumatoria total de depósitos calculada correctamente. 	Exitoso 
CP08	Correo por depósito 	Registro de $100.000 (Juan Pérez) 	Notificación automática enviada al apoderado. 	Exitoso 
CP09	Correo aporte común 	Registro fondo común: $20.000 	Notificación enviada al representante del curso. 	Fallido 
CP10	Reporte gerencial 	Clic en vista "Dueño" 	Despliegue de listado de colegios con su avance. 	Exitoso 
