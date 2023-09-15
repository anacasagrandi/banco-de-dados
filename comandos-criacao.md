# Comandos SQL - Referência
<!--_____________________________________________________ -->
## Modelagem física

### Criar Banco de dados

```sql
CREATE DATABASE vendas CHARACTER SET utf8mb4;
```

### Criar a tabela fabricantes
```sql
CREATE TABLE fabricantes(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(45) NOT NULL
)
```
### Criar a tabela produtos
```sql
CREATE TABLE produtos(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(45) NOT NULL,
    descricao TEXT(1000) NOT NULL,
    preco DECIMAL(6,2) NOT NULL,
    quantidade TINYINT(4) NOT NULL
)
```

### Adicionar campo/coluna em uma tabela
```sql
ALTER TABLE produtos ADD fabricantes_id INT NOT NULL
AFTER quantidade;
```

### Criação da chave estrangeira (relacionamento entre tabelas)
```sql
ALTER TABLE produtos
    # CONSTRAINT é uma restrição definitiva no relacionamento
    ADD CONSTRAINT fk_produtos_fabricantes

FOREIGN KEY (fabricantes_id) REFERENCES fabricanres (id)
```

