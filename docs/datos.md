## De almacenes a entidades

| Almacén del DFD | Qué guarda (una oración) | Entidad candidata | Identificador |
|---|---|---|---|
|D1 Socios |Guarda los datos personales y de identificación de cada socio registrado en el gimnasio. |Socio |@num_socio |
|D2 Membresías |Guarda la información de las membresías contratadas por los socios y su vigencia. |Membresía |@id_membresia |
|D3 Pagos |Guarda los pagos realizados por los socios, incluyendo el importe y la fecha del pago. |Pago |@folio_pago |
|D4 Asistencias |Guarda los registros de entrada de los socios al gimnasio con su fecha y hora. |Asistencia |@id_asistencia |

La entidad Pago relaciona al Socio con la Membresía, ya que permite identificar quién realizó el pago y a qué membresía corresponde. Además, tiene datos propios, como el importe y la fecha del pago, por lo que debe considerarse una entidad independiente en el modelo entidad/relación.

 ## Diccionario de datos.

Definición de almacenes

Socio = @num_socio + nombre + apellidos + telefono + correo

Membresía = @id_membresia + num_socio + tipo_membresia + fecha_inicio + fecha_fin + estado_membresia

Definición de flujos

Solicitud de registro de socio = nombre + apellidos + telefono + correo flujo que entra al sistema

Confirmación de registro de socio = num_socio + nombre + resultado_registro flujo que sale del sistema

Valores posibles de un dato con estados o categorías

estado_membresia = ["vigente" | "vencida" | "suspendida"]

