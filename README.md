#Práctica 3 - Unidad 2

**Título: Sistema de Gestión de Flota para una Empresa de Transporte**

**Descripción:**
Se requiere desarrollar un sistema de gestión de flota para una empresa de transporte que opera con tres tipos de vehículos: coches, camiones y motocicletas. El sistema debe ser implementado como una aplicación de línea de comandos y debe cumplir con los siguientes requerimientos:

1. **Clases de Vehículos:**
    - `Coche`: Representa un coche con un número de identificación único, capacidad de pasajeros y cálculo de costo de viaje.
    - `Camion`: Representa un camión con un número de identificación único, capacidad de carga en toneladas y cálculo de costo de viaje.
    - `Motocicleta`: Representa una motocicleta con un número de identificación único, cilindrada y cálculo de costo de viaje.
    - Subclases de `Camion`:
        - `CamionPlataformaAbierta`
        - `CamionConLona`
        - `CamionFrigorifico` (con diferentes tipos: refrigerado, congelado, etc.)
        - `CamionCisterna` (para transportar líquidos: físico-químicos, tóxicos, etc.)
        - `CamionCerrado`
        - `CamionPortacoches`
        - `CamionJaula`
        - `CamionContenedor`

2. **Usuarios:**
    - `Administrador`: Puede agregar, editar y eliminar vehículos y usuarios.
    - `Gerente`: Puede ver estadísticas, generar reportes y administrar la flota.
    - `UsuarioDeCaja`: Puede registrar transacciones de pago y generar facturas.

3. **Cálculo del Costo del Viaje:**
    - Para cada vehículo, se debe calcular el costo del viaje considerando la distancia y el consumo de combustible por kilómetro. El costo puede variar según el tipo de vehículo y el tipo de carga transportada.

4. **Búsqueda de Vehículos:**
    - Los clientes pueden buscar vehículos por número de identificación o por capacidad de carga.

5. **Requerimientos No Funcionales:**
    - **Usabilidad**: La interfaz de línea de comandos debe ser intuitiva y fácil de usar.
    - **Precisión**: La información almacenada debe ser precisa y confiable.
    - **Disponibilidad**: El sistema debe estar disponible durante el horario de operación de la empresa.
    - **Seguridad**: La información debe estar protegida contra accesos no autorizados.
    - **Escalabilidad**: El sistema debe manejar un alto volumen de transacciones.
    - **Mantenibilidad**: El sistema debe ser fácil de mantener y actualizar.
    - **Rendimiento**: El sistema debe responder eficientemente incluso bajo carga.

Este sistema permitirá a la empresa gestionar la flota de vehículos de manera eficiente y brindar un servicio de transporte confiable a sus clientes.

  > **Nota:**
  >
  > Se deberá generar el proyecto maven correspondiente. Se deberán generar los test unitarios de cada clase y los test de integración.
