# SistemaAdmConsultasHospitalN
SISTEMA WEB DE ADMINISTRACION DE CONSULTAS MEDICAS PARA OPTIMIZAR SU ADMINISTRACION

PROBLEMA

El seguro universitario de salud tiene problemas al gestionarlas consultas a los pacientes, ay largas filas y hace falta un sistema que de la comodidad de administrar consultas.

PROPUESTA GENERAL DE SOLUCIÓN

Elaborar un sistema que permita hacer reservas a consultas de hospitales de primer, segundo y tercer nivel. Reservar un cupo a posibles pacientes, realizar un traspaso a un hospital especializado de segundo o tercer nivel con la autorizacion y el administrador del hospital  de primer nivel. Poder tener notificaciones de consultas, datos del paciente, doctor, posibles cambios de horario si fuera necesario.

VALOR PARA EL NEGOCIO

Es sistema de reservas ayudara en gran manera a los pacientes evitando largas colas y propagacion del covid. Permitira que los pacientes tengan notiificaciones para que no olviden sus citas medicas. Permitira hacer un traspaso rapido y definir rapidamente un horario de cita. Optimizar el tiempo de asignacion de personal a los posibles pacientes. 

TANGIBLE

* Obtener notificaciones acerca de consultas proximas
* Evitar colas largas para reserva de consulta.
* Reducir los pasos para un traspaso de hospital para el pacientes

INTANGIBLE

* Mayor comodidad de los pacientes
* Mayor comodidad de los medicos
* Mayor facilidad para los administradores

FACTIBILIDAD (ANÁLISIS DE RIESGOS)

ECONOMICA

* El sistema costara 25000 bs.

TECNICA

* Se necesitará diseñar la base de datos en postgres.
* Se necesitara capacitacion para el uso del sistema
* Se necesitara un servidor para alojar a el sisttema

LISTADO DE REQUERIMIENTOS CON HISTORIAS DE USUARIOS




Modulo pacientes


Como paciente del hospital … quiero poder hacer reservas mediante un sistema web de forma que no tenga largas colas y posiblemente tener que acudir otros dias  para conseguir una ficha.
Como paciente quiero poder ver un listado de todas las reservas que tengo para poder estar al tanto de estas
Como paciente quiero poder cambiar el horario de consulta si es posible de forma que pueda controlar imprevistos
Como paciente quiero pder cancelar la consulta.en un periodo posible de forma que no reserve una ficha no pueda asistir y tenga alguna sancion





Modulo administrador


Como administrados quiero poder registrar consultas de pacientes para aquellos pacientes que vengan al hospital a hacer su consulta y no puedan hacerlo mediante el sistema de forma que paciente que no utilicen estas tecnologias tengan un horario seguro de atencion
Como administrador quiero poder eliminar o modificar reservas de consulta en caso de encontrar alguna incoherencia de forma que se controle los datos necesarios para la consulta
Como administrador quiero poder ver solicitudes de modificacion y cancelacion de consultas para confirmar o  en todo negar y establecer una  sancion
Como administrador quier poder confirmar, negar y llenar los traspasos de los pacientes.





Modulo medicos


Como medico quiero poder administrar el listado de pacientes, listado de consultas de acuerdo a las fechas que tengo de forma que me facilite la atencion de estos
Como medico quiero poder solicitar traspasos de forma que sea mas facil el llenado de formulario de traspaso y pueda ser controlado por un administrador de traspasos
Como medico quiero poder registrar los pacientes atendidos, pacientes faltantes y pacientes atrasados que me facilite tener un historial para poder administrar mejor las consultas
Como medico quiero poder registrar la historia del usuario mas facilmente en el sistema, podiendo registrar al final de la consulta historia del paciente, solicitudes de traspaso o laboratorios y recetas que se daran al paciente.

    • El proyecto debe tener mínimo 3 módulos.
    • Deben usar base de datos Mysql o PostgreSQL
    • En cada módulo como mínimo deben tener 4 API’s.
    • Los listados deben tener paginación(si se requiere)
    • Frontend -> Angular (versión 13)
    • Backend -> Spring Boot
