#  Taller práctico 03: Ecosistema Odoo

## Paso a apaso he realizado lo siguiente

### 1. Preparación del entorno

- Comprobé que los contenedores de Docker de Odoo  estuvieran funcionando correctamente.
- Utilicé los logs de Docker para observar los procesos internos del sistema.
- Activé el Modo Desarrollador de Odoo.

### 2. Instalación de módulos

- Instalé los módulos de: Facturación, conversación, inventario y ventas

### 3. Importación de clientes

- Creé un archivo `clientes_mock.csv` con datos de prueba.
- Importé los clientes desde Odoo utilizando la herramienta de importación.

### 4. Ciclo de negocio en Odoo

- Creé un presupuesto para un cliente.
- Añadí un producto almacenable que sería un portatil asus en este caso
- Confirmé el pedido y validé la entrega.
- Generé una factura integrada con ventas e inventario.

### 5. Modificación de informes PDF

- Accedí a las vistas técnicas de Odoo.
- Modifiqué la plantilla `sale.report_saleorder_document`.
- Añadí el aviso legal y texto de protección de datos proporcionado usando XML .
- Verifiqué el resultado final en el PDF generado.

### 6. Exportación de información
- Exporté clientes desde Odoo en formato CSV.
- Seleccioné campos relacionados e hice que el país del cliente se viera con su respectivo nombre.
- Comprobé la codificación UTF-8 en VS Code.

