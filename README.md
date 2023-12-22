 ## Trabajo Práctico Integrador Base de Datos

Se deberá crear una base de datos llamada “integrador_cac” y crear la siguiente tabla llamada “oradores”:

Definir los tipos de datos correspondientes
Definir la clave primaria correspondiente
Definir las restricciones correspondientes
Insertar 10 registros
Hacer un backup de la base de datos


CREATE DATABASE integrador_cac;

USE integrador_cac;

CREATE TABLE oradores (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(50) NOT NULL,
    especialidad VARCHAR(50) NOT NULL,
    pais VARCHAR(50) NOT NULL,
    email VARCHAR(50) UNIQUE NOT NULL
);

INSERT INTO oradores (nombre, especialidad, pais, email) VALUES
('Olga Granados', 'Locutor', 'Argentina', 'olgag@hotmail.com'),
('Lito Carunchio', 'Analista en sistemas', 'Argentina', 'litoc@hotmail.com'),
('Romina Romero', 'Pastelera', 'Argentina', 'pompisr@hotmail.com'),
('Evelyn Manzano', 'Profesora', 'Argentina', 'eveman@hotmail.com'),
('Martina Jimenez', 'Contadora', 'Argentina', 'Martinam@hotmail.com'),
('Estela Maldo', 'Escultora', 'Argentina', 'estela-m@hotmail.com'),
('Leal Aballay', 'Técnico', 'Argentina', 'leal-l@hotmail.com'),
('Candela Tim', 'Profesora', 'Argentina', 'Cande-t@hotmail.com'),
('Henry Ford', 'orador', 'Argentina', 'henry-f@hotmail.com'),
('Andy Pallares', 'Locutor', 'Argentina', 'andy@hotmail.com'),
('Kevin Bianco', 'Orador', 'Argentina', 'kevin@hotmail.com'),
('Jose Cascio', 'Orador', 'Argentina', 'joseb@hotmail.com'),
('Agustina Herrera', 'Arquitecto', 'Argentina', 'agus-h@hotmail.com'),
('Veronica Fraga', 'Contador', 'Argentina', 'verof@hotmail.com'),
('Lucia Salgado', 'Cantante', 'Argentina', 'lucis@hotmail.com');
