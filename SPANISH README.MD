# LF Decentralized Trust Labs
LF Decentralized Trust Labs proporciona un espacio (es decir, repositorios de GitHub) donde el trabajo puede comenzar fácilmente sin la necesidad de crear un proyecto. Consulte la página wiki de LF Decentralized Trust Labs para obtener información adicional.

Proceso para proponer un nuevo laboratorio
1. Bifurque (fork) el repositorio lf-decentralized-trust-labs.github.io.

2. Complete la Plantilla de Propuesta y guárdela en el subdirectorio de laboratorios con el nombre de su laboratorio, por ejemplo, minuevolaboratorio.md. Se espera que su repositorio de laboratorio tenga el mismo nombre, así que téngalo en cuenta.

3. En la Plantilla de Propuesta, hay una entrada para patrocinador(es). Aunque no es obligatorio, se anima a los proponentes a buscar un patrocinador que pueda ayudarlos a crear vínculos con el resto de la comunidad de LF Decentralized Trust y garantizar que la propuesta sea coherente y novedosa (en concepción, ejecución propuesta o comunidad interesada).

Para encontrar patrocinadores:

a. Utilice sus conexiones con proyectos existentes y pregunte a los mantenedores.

b. Busque grupos de trabajo o proyectos afines al laboratorio propuesto y presente el proyecto (es recomendable tener la plantilla ya completada) en los canales y/o listas de correo asociados. Los correos de los presidentes de los grupos de trabajo, los contactos de los mantenedores, etc., se pueden encontrar en el wiki o en GitHub. Haga solicitudes personales si es posible. Cada repositorio contiene un archivo MAINTAINERS que enumera a los mantenedores actuales con su información de contacto, y puede contactarlos a todos publicando en la lista de Mantenedores.

4. Confirme (commit) sus cambios con la firma correspondiente. Esto significa que el mensaje de registro de su confirmación debe contener una línea que se vea así, con su nombre y dirección de correo electrónico reales:


Signed-off-by: Juan Pérez <juan.perez@ejemplo.com>
Agregar la bandera -s a su comando git commit agregará esa línea automáticamente. También puede agregarla manualmente como parte del mensaje de registro de su confirmación o agregarla después con git commit --amend -s.

5. Envíe una Solicitud de Extracción (Pull Request).

Los administradores de laboratorios revisarán su propuesta. Al igual que los patrocinadores, los administradores no tienen responsabilidades más allá de esto; el trabajo continuo, como contribuir con código o revisiones, no está ligado a su rol como administradores. Al revisar la propuesta, los administradores se aseguran de que la propuesta sea coherente y novedosa (en concepción, ejecución propuesta o comunidad interesada).

Incorporación de un repositorio existente
Por defecto, los administradores de laboratorios crearán un nuevo repositorio para que comience, pero si tiene un repositorio de GitHub existente que le gustaría incorporar a su laboratorio propuesto, tiene la opción de solicitar que se reutilice ese repositorio. Sin embargo, esto solo es posible si cada confirmación (commit) en su repositorio existente está firmada, para que no haya problemas relacionados con el DCO. Si ese no es el caso, deberá incorporar su código comprimiendo todas sus confirmaciones en una sola confirmación inicial realizada en su nuevo repositorio de laboratorio con su firma.

Requisito de licencia
# Todo el software de LF Decentralized Trust debe estar disponible bajo una licencia Apache 2.0. Esto se aplica a los Laboratorios. Asegúrese de licenciar todo el código entrante y nuevo de acuerdo con esto, y garantice que todas las confirmaciones se realicen con la firma correspondiente para que no se introduzcan problemas relacionados con el DCO.
