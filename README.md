#TabelaLegumesSQL

-- Criação da tabela legumes
CREATE TABLE legumes (
    id INT PRIMARY KEY,
    nome VARCHAR(50)
);

-- Inserção dos legumes mais consumidos
INSERT INTO legumes (id, nome)
VALUES (1, 'Abóbora'),
       (2, 'Abobrinha'),
       (3, 'Alcachofra'),
       (4, 'Aspargos'),
       (5, 'Batata-doce'),
       (6, 'Berinjela'),
       (7, 'Beterraba'),
       (8, 'Cenoura');
