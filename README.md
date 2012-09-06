laGauchada
==========

Aplicación para administrar un banco de tiempo gratuito

Definiciones:
--

**Miembro** = Usuario del sistema

**Creditos** = Unidad de intercambio, se mide en minutos y es una unidad entera

**Gauchada** = Trabajo realizado por uno o más miembros a favor de otro miembro. Debe retribuirse con creditos disponibles o prestados por el banco.

Reglas
--

**Sobre los creditos**

El Banco puede entregar "creditos" a los miembros del sistema para que puedan encargar "Gauchadas". En esta entrega de "creditos" por parte del banco se exigirán intereses en "creditos" adicionales a los entregados determinables al momento de la entrega.

Todos los miembros del sistema deben "pagar" las "gauchadas" mediante "créditos". 

**Sobre las gauchadas** 

Toda "gauchada" debe indicar claramente:
* Lugar donde se llevará a cabo 
* Fecha en la que se deberá llevar a cabo (puede modificarse luego de una negociación)
* Estimación del tiempo esperado para la realización de la tarea, si consumiera más tiempo del estimado deberán pagarse intereses por el tiempo adicional al estimado inicialmente que será percibido por los miembros que se prestaron para colaborar. 
* Si el solicitante de la "gauchada" la cancelara luego de pasada la fecha acordada y se haya aprobado su ejecución, deberán pagarse los créditos convenidos al miembro comprometido aunque no se haya completado la tarea. Sólo es posible aplicar una penalización en el pago al colaborador en caso que no se haya completado por culpa de este. 

**Sobre la reputación de los miembros**

Debido a que el sistema funciona en base a la confianza de los miembros entre sí. Se establece un sistema de reputación basado en premios y penalidades sobre las "gauchadas" en las cuales colaboró. 

Se permitirá a quien encarga una tarea premiar o penalizar luego de la ejecución de una tarea en hasta un 50% sobre el tiempo estimado para su realización. 

La reputación aumentará cuantos más premios reciba y empeorará en la medida que aumenten las penalidades en su contra. Tambien se tendran en cuenta para la reputación los premios y penalidades entregados:
* Un colaborador que reciba penalidades en forma frecuente encotrará dificultades para acordar su colaboración en "gauchadas" debido a que esta situación será reflejada hacia el meimbro que la encarga.
* A un miembro que entregue frecuentemente penalidades se le difilcultará encontrar colaboradores para sus gauchadas

Plataformas
--

Al estar el core de la aplicación en APIs (rest expresada en JSON) se permitirá desarrollar en multiples plataformas. La propuesta inicial es desarrollar 2 plataformas principales.

* Android
* Web 

