Los campos `capacidad` y `nivel` se declararon como privados para aplicar un encapsulamiento estricto, impidiendo que clases externas los modifiquen directamente y alteren la integridad del objeto. 

El invariante protegido garantiza que el nivel de combustible nunca sea negativo ni supere la capacidad máxima establecida en ningún momento. 

Cualquier alteración del estado pasa obligatoriamente por los métodos validados de la clase.