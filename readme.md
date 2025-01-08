### Diagramar con UML

Ahora que tienes una mejor comprensión sobre la diagramación, es momento de analizar algunos casos. En cada uno de ellos, tendrás que identificar los atributos, las responsabilidades y el constructor más adecuado según el contexto. Después, crearás los diagramas de clases usando DrawIO.

### Ejercicio N° 1

**Caso:**
Imagina que el tío Rico tiene una cuenta en el banco **UAGro Bank**. Cada vez que realiza un retiro, verifica varios aspectos de su cuenta: 

- Que el nombre del titular sea el suyo. 

- Que el saldo esté correcto. 

- Que el número de la cuenta también sea el adecuado.

El tío acaba de empezar a usar la página web de su banco, que le permite:

- Retirar.

- Depositar.

- Recibir transferencias a través de su número de cuenta.

Para acceder a su cuenta, necesita que le muestren:

- Su saldo.

- El titular de la cuenta.

- Su número de cuenta.

- Su alias.

Cuando abrió su cuenta de caja de ahorros, le pidieron:

- Su nombre.

- El saldo inicial.

Con ese número que le asignaron, quedó registrada su cuenta.

**Actividad:**

Modela la clase `CajaDeAhorros` para que sea utilizada en un sistema del banco. Agrega los atributos y métodos que consideres necesarios para cubrir los requerimientos del ejercicio. Recuerda pensar en un constructor adecuado para esta clase.

### link para ver el ejercicio resuelto

https://drive.google.com/file/d/1IB7eJtTG3nIwmVQ5qbJQsp6qpekEKEcX/view?usp=drive_link

### Ejercicio N° 2

**Caso:**

Daniel es cliente de **UAGro Bank** y tiene una cuenta corriente que le permite emitir cheques para realizar pagos de electrodomésticos. El banco ofrece dos tipos de cheques:  

- **Cheque común.**  

- **Cheque de pago diferido.**

Cada cheque tiene:  

- Una fecha de emisión.  

- Una fecha de vencimiento.  

Además, el cheque puede ser transferido a otras personas mediante un **endoso**, lo cual significa que Daniel debe escribir en el reverso del cheque los datos del nuevo propietario. Los cheques tienen un plazo máximo de 30 días desde la fecha de vencimiento para ser presentados.

**Actividad:**

Modela la clase `Cheque` para que pueda ser utilizada en un programa del banco. Incluye los atributos, métodos y un constructor adecuado para que refleje las funcionalidades mencionadas.

### link para ver el ejercicio resuelto:
 
https://drive.google.com/file/d/1qHAES2-tGj9Nt3D2FCZKBYQnyogiexu7/view?usp=drive_link

### Ejercicio N° 3

**Caso:**

Un día cualquiera en la veterinaria, llega el joven pitbull llamado **Dorian**, acompañado de su dueño **César**.  

El veterinario **Julio** lo está esperando en el consultorio 1 para atenderlo, mientras que, en el consultorio 2, sale el gatito **Lito Rodríguez**, que tiene 4 años.  

**Observaciones:**

- Cada veterinario tiene asignado un consultorio.  

- Durante las consultas:

- Las mascotas son pesadas.

- Las mascotas son medidas.

- Se registra su estado de salud: _regular, bueno o muy bueno._  

Los clientes acostumbran pagar las consultas a fin de mes, acumulándose:

- El importe de las consultas.

- La cantidad de consultas realizadas.

**Actividad:**

Identifica las clases que se mencionan en la narrativa y modela un diagrama de clases. Define los atributos, métodos y constructores correspondientes a cada clase que debe intervenir en este proceso.

### link para ver el ejercicio resuelto:

https://drive.google.com/file/d/1hf98GkxbanocWs2XGBVTfQBOdVBGWTbt/view?usp=drive_link

### Ejercicio N° 4

**Caso:**

La veterinaria siempre necesita tener cajas de provisiones para revender o para usarlas durante las consultas de los animales. Estas cajas tienen varias características importantes, como:  

- Peso total.  

- Origen.  

- Nombre del proveedor.  

- Descripción del contenido.  

- Si se debe manejar con cuidado, en caso de que el contenido sea frágil.  

**Actividad:**

Identifica los atributos y métodos que debería tener la clase `CajaDeProvisiones`. Considera agregar un constructor adecuado y modela esta clase utilizando UML. Asegúrate de que refleje todas las necesidades mencionadas en el planteamiento.

### link para ver el ejercicio resuelto: 

https://drive.google.com/file/d/14gH_BO_-y_abHKDoc6Rp-6ytQRwCqvA1/view?usp=drive_link

