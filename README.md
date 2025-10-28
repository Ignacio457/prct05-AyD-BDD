# prct05-AyD-BDD

## Consultas y Vistas


### ventas totales por categoría de películas

![ventas totales por categoría de películas](./1.png)

---

### ventas totales por tienda,

![ventas totales por tienda](./2.png)

---

### lista de películas
![lista de películasa](./3.png)

---

### información de los actores
![información de los actores](./4.png)

---

## Restricciones CHECK 

![Restricciones CHECK](./5.png)

---

## Explique la sentencia que aparece en la tabla customer 

  last_updated BEFORE UPDATE ON customer 
  FOR EACH ROW EXECUTE PROCEDURE last_updated()


Su propósito es actualizar automáticamente el campo last_update con la fecha y hora actuales (NOW()), antes de cada actualización (BEFORE UPDATE)

Se utiliza también en la tabla actor.

## Disparadores

![Disparador 1](./6.png)

---

![Disparador 2](./7.png)
