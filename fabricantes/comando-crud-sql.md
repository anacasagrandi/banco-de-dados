# Comandos SQL - Para CRUD (Referência)

## Resumo

### Resumo
C --> Create (Insere dados)
R --> Read (ler dados)
U --> Update (atualizar dados)
D --> Delete (Deletar dados)
<!-- _____________________________________ -->

## Insert
## Fabricantes

```sql
INSERT INTO fabricantes (nome) VALUES ('Asus');
INSERT INTO fabricantes (nome) VALUES ('Dell');
INSERT INTO fabricantes (nome)
VALUES ('Apple'), ('LG')('Samsung') ('Brastemp');
 
```

## Insert
## Produtos

```sql
INSERT INTO produtos (nome,descricao, preco, quantidade, fabricante_id) VALUES (
'Ultrabook',
'Ultrabook Asus Intel Core i9', 
 6500.99,
 7,
 1
 );

 INSERT INTO produtos (nome,descricao, preco, quantidade, fabricante_id) VALUES (
'Geladeira',
'FrostFree com acesso a internet', 
 8500.99,
 10,
 6
 );

INSERT INTO produtos (nome,descricao, preco, quantidade, fabricante_id) VALUES (
'Tablet Android',
'Tablet 10 polegadas', 
 4999.99,
 3,
 5
 );

INSERT INTO produtos (nome,descricao, preco, quantidade, fabricante_id) VALUES (
'Iphone 14 Pro Max',
'Processador Bionic 15 com 512Gb de armazenamento', 
 9999.97,
 3,
 3
 );

 INSERT INTO produtos (nome,descricao, preco, quantidade, fabricante_id) VALUES (
'Gabriel Gonçalves da Silva',
'Gab Silvete', 
 1.99,
 1,
 3
 );
```

## Insert
## Fabricantes

```sql
INSERT INTO fabricantes (nome) 
VALUES ('Positivo'), ('Microsoft');
 
```

### Insert 
### Produtos
```sql
INSERT INTO produtos (nome,descricao, preco, quantidade, fabricante_id) VALUES (
'Xbox',
'Console de ultima geração...', 
 2500,
 6,
 8
 );

 INSERT INTO produtos (nome,descricao, preco, quantidade, fabricante_id) VALUES (
'Ultrabook',
'AMD Ryzen 5 16GGb RAM...', 
4500.97,
 12,
 7
 );
 
```