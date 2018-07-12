# Vender un dispositivo a una entidad usuaria

**Pasos para realizar una venta con devicehub**

1. La distribuidora informa los posibles compradores de los dispositivos disponibles. Para enviar la informacion, exporta los dispositivos registrados en devicehub y comparte el documento exportado con el posible comprador.
2. El posible comprador realiza su pedido enviando una lista con los IDs de los dispositivos que quiere adquirir.
3. La distribuidora finaliza la factura y los convenios de eReuse
4. Cuando la factura y los convenios son finalizados, el comprador debe pagar la factura y recoger o recibir los dispositivos. Al recibir o recoger los dispositivos, se debe registrar el evento RECEIVE para los dispositivos vendidos. Ademas, la entidad distribuidora debe registrar el evento SELL para los dispositivos vendidos.

La entidad distribuidora debe guardar:

* el nombre y los datos de la entidad compradora/usuaria \(tipologia, ubicación, etc.\)
* el convenio con el usuario final
* el importe pagado por el usuario

También debe mantenerse informado si el dispositivo sigue en uso o no y guardar esta información.

**¿Qué hacer si los dispositivos están en el inventario devicehub de otra entidad?**

Para migrar los dispositivos al inventario propio, sigue los pasos de compartir un dispositivo con otras entidades, reservar un dispositivo y finalizar la reserva. Los dispositivos deben ser migrados al inventario devicehub de la entidad distribuidora antes de enviar los eventos RECEIVE y SELL \(punto 4\).

