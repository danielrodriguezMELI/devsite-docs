# Configurar pagos con Checkout Pro (Checkout Mercado Pago)
 
Al instalar [Checkout Pro](/developers/es/docs/checkout-pro/landing), puede haber un **aumento en la tasa de aprobación de las ventas en la tienda en línea**. Esto sucede porque los compradores podrán pagar con una cuenta de Mercado Pago y todo el proceso de compra se realizará en nuestro entorno, lo que facilita el pago. Al final de la transacción, estos compradores son redirigidos al entorno de la tienda.
 
Para integrar Checkout Pro, sigue los pasos a continuación.
 
1. En el Panel Administrativo de tu Tiendanube, accede a **Mis aplicaciones > Ver todas las aplicaciones**. 
2. Localiza el plugin Mercado Pago en la lista de aplicaciones y haz clic en **Configurar aplicación**.
3. En la lista de métodos de pago, localiza el plugin Mercado Pago y haz clic en **Editar**.
----[mla, mlb, mpe, mco, mlu, mlc]---- 
4. Para aplicar un "valor mínimo de cuotas" para los pagos, informa el monto en el campo disponible.
------------
----[mlm]---- 
4. Para aplicar un "valor mínimo de la mensualidad" para los pagos, informa el monto en el campo disponible.
------------
----[mla, mlm, mpe, mco, mlu, mlc]---- 
5. Si deseas aplicar descuentos para pagos con Checkout API, **informa el porcentaje** para pagos en efectivo y tarjetas (crédito y débito).
------------
----[mlb]---- 
5. Si deseas aplicar descuentos para pagos con Checkout Transparente, **informa el porcentaje** para pagos con boleto, tarjeta de crédito y Pix.
------------
6. Si deseas aplicar descuentos para pagos con Checkout externo (Checkout Pro / Checkout Mercado Pago), **informa el porcentaje** en el campo disponible.
7. Para configurar las experiencias de pago de su tienda, haz clic en **Editar en el sitio de Mercado Pago**.
8. En el Checkout Mercado Pago, elige las formas de pago que quieres ofrecer en el entorno de pago de Mercado Pago, las cuales pueden ser:
----[mla, mpe, mco, mlu, mlc]---- 
 * **Tarjeta de crédito**. Elige también el número máximo de cuotas permitidas.
 * **Tarjeta de débito**.
 * **Otros medios de pago**. Elige también el número de días para vencimiento del ticket (incluye sábado y domingo). 
------------ 
----[mlb]---- 
 * **Tarjeta de crédito**. Elige también el número máximo de cuotas permitidas.
 * **Tarjeta de débito**.
 * **Otros medios de pago**. Elige también el número de días para vencimiento del ticket (incluye sábado y domingo). Además, la opción de pago con Pix solo se mostrará si existe una llave Pix registrada en Mercado Pago. Si aún no las creaste, [haz clic aquí](https://www.youtube.com/watch?v=60tApKYVnkA) y consulta el paso a paso.
------------ 
----[mlm]---- 
 * **Tarjeta de crédito**. Elige también el número máximo de meses permitidos.
 * **Tarjeta de débito**.
 * **Otros medios de pago**. Elige también el número de días para vencimiento del ticket (incluye sábado y domingo).
------------
9. Finalmente, haz clic en **Guardar cambios**.

<center>

![Payments Checkout Pro - Nuvemshop](/images/nuvemshop/cho-pro-es.gif)

</center>

¡Listo! Checkout Pro está listo para recibir pagos de tu tienda.