# Atower S.A.S

## Documentación API REST Sisma Salud

### Endpoint: `GET api/consultarEps`

#### Autenticación
Baerer Token requerido

#### Respuesta de ejemplo

```json
[
  {
    "codigoEmpresa": "00",
    "nombreEmpresa": "prueba"
  }
]
```


### Endpoint: `GET api/consultarPaciente?paciente=1234567`

#### Autenticación
Baerer Token requerido

#### Respuesta de ejemplo

```json

  {
    "pacienteExiste": True,
    "nombre1Paciente": "",
    "apellido1Paciente": "",
    "celular": 0,
    "ciudad": "",
    "direccion": ""
  }

```

### Endpoint: `POST api/guardarPaciente`

#### Autenticación
Baerer Token requerido

#### Request de ejemplo

```json

  {
    "tipoIdentificacion": "",
	"numeroIdentificacion": "",
    "primerNombre": "",
	"primerApellido":"",
	"fechaNacimiento":"1996-09-29",
	"sexo":"M",
	"ciudad":"",
   	"direccion":"",
	"correo":"",
	"telefono":0,
  }

```
### Response
```
{
	"message":"Paciente Guardado con exito",
	"exito": True
}
```
