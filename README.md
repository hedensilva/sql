CREATE TABLE vendas (
    id_venda INT PRIMARY KEY,
    cliente VARCHAR(50),
    produto VARCHAR(50),
    categoria VARCHAR(30),
    quantidade INT,
    preco_unitario DECIMAL(10,2),
    data_venda DATE
);

INSERT INTO vendas VALUES
(1, 'Ana', 'Notebook', 'Informática', 1, 3500.00, '2025-01-10'),
(2, 'Bruno', 'Mouse', 'Periféricos', 2, 80.00, '2025-01-12'),
(3, 'Carla', 'Teclado', 'Periféricos', 1, 120.00, '2025-01-15'),
(4, 'Daniel', 'Monitor', 'Informática', 1, 950.00, '2025-01-18'),
(5, 'Eduardo', 'Impressora', 'Periféricos', 1, 650.00, '2025-02-02'),
(6, 'Fernanda', 'Notebook', 'Informática', 2, 3400.00, '2025-02-05'),
(7, 'Gustavo', 'Headset', 'Periféricos', 3, 150.00, '2025-02-10'),
(8, 'Helena', 'Cadeira Gamer', 'Móveis', 1, 1200.00, '2025-02-14'),
(9, 'Igor', 'Mesa Gamer', 'Móveis', 1, 800.00, '2025-02-15'),
(10, 'João', 'Notebook', 'Informática', 1, 3600.00, '2025-02-20'),
(11, 'Karen', 'Mousepad', 'Periféricos', 2, 45.00, '2025-02-25'),
(12, 'Lucas', 'Monitor', 'Informática', 2, 970.00, '2025-03-01'),
(13, 'Marina', 'Cadeira Gamer', 'Móveis', 1, 1300.00, '2025-03-04'),
(14, 'Nicolas', 'Notebook', 'Informática', 1, 3550.00, '2025-03-10'),
(15, 'Olivia', 'Teclado', 'Periféricos', 1, 110.00, '2025-03-12'),
(16, 'Paulo', 'Mouse', 'Periféricos', 3, 85.00, '2025-03-15'),
(17, 'Quésia', 'Mesa Gamer', 'Móveis', 1, 900.00, '2025-03-20'),
(18, 'Rafael', 'Impressora', 'Periféricos', 1, 670.00, '2025-03-22'),
(19, 'Sofia', 'Headset', 'Periféricos', 2, 160.00, '2025-03-25'),
(20, 'Tiago', 'Monitor', 'Informática', 1, 940.00, '2025-03-30');
