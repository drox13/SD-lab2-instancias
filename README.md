# SD-Lab2-instancias
Construir un sistema similar al anterior pero que permita realizar un balanceo de carga en un servicio que recibe como parámetro una imagen y le pone un texto de una frase famosa en la parte inferior(se obtiene de un web service externo de terceros). Es decir cuando se realice una petición al middleware tiene que llevar un control de a quien le toca responder la petición basado en un sistema de turnos. Adicionalmente crear un servicio en el middleware que permita crear un nueva instancia y agregarla a la lista de servidores del balanceo de carga en caso de ser necesario y otro que a través de un consumo de servicios envíe una notificación por correo cuando un servidor no responda.