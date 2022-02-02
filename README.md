# Cadastro de séries

Neste projeto foi criado um APP simples de cadastro de séries em .NET com o conceito de CRUD.

A classe EntidadeBase foi criada só para ter um Id para as classes que herdarem dela.

A classe Serie herda da classe EntidadeBase.

A classe SerieRepositorio implementa a interface IReposiotoio.

A interface IRepositorio determina os métodos de listagem, retornar o Id, inserir, excluir, atualizar e proximoId garantindo, assim que as
classes que a herdarem tenham esses métodos.

O programa principal monta o cadastro em série, usando o banco de dados em memória com o uso de lista da classse SerieRepositorio.

## CRUD

**C**reate / Criar

**R**ead / Ler

**U**pdate / Atualizar

**D**elete / Excluir

## Criando o console

dotnet new console -n DIO.Series

## Abrir o projeto

code DIO.Series/


