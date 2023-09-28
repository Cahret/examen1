CREATE DATABASE bd_Medicamento;
USE bd_Medicamento;
-- Crear la tabla "Medicamento"
CREATE TABLE Medicamento" (
    id_Medicamento INT AUTO_INCREMENT PRIMARY KEY,
   Nombre  VARCHAR(255),
   Descripción  VARCHAR(50),
    Categoria VARCHAR(50),
  Precio  DECIMAL(10,2)
Stock   INT
    FechaVencimiento  DATE,
    Provedor VARCHAR(100)
);
-- Insertar 5 Medicamentos
INSERT INTO MEDICAMENTOS (Medicamento, Nombre, Descripción, Categoría, Precio, Stock,Fecha de vencimiento, Proveedor)
VALUES
    ('1', 'Paracetamol', 'Analgésico común', 'Analgésico '5', '100', '2024-12-31', 'Genérico Pharma')
       ('2', 'Amoxicilina', 'Antibiótico', 'Antibiótico',  '10.5', '50', '2023-11-15', 'Farmacia A')
    ('1', 'Vitamina C', 'Suplemento Vitamínico', 'vitamina', '5', '100', '2024-08-01', 'Proveedor B')
    ('1', 'Ibuprofeno', 'Antiinflamatorio', 'Analgésico ', '5', '100', '2023-10-20', 'Genérico Pharma')
    ('1', 'Omeprazol', 'Medicamento', 'Gi', '5', '100', '2023-12-10', 'Farmacia A')
