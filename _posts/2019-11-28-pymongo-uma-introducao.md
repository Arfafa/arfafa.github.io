---
layout: post
title: "PyMongo: Uma Introdução"
date: 2019-11-28
image: '/assets/img/'
description:
tags:
 - Python
 - MongoDB
 - PyMongo
---

# Índice
1. [Instalação](#Instalação)
2. [Tutorial](#Tutorial)

## Instalação

É recomendado utilizar o pip para instalar o pymongo em qualquer plataforma:

```bash
$ python -m pip install pymongo
```

Para baixar uma versão específica:

```bash
$ python -m pip install pymongo==3.5.1
```

Para atualizar usando o pip:

```bash
$ python -m pip install --upgrade pymongo
```

## Tutorial

### Pré-requisitos:

Antes de começar você precisar ter o [MongoDB](https://docs.mongodb.com/manual/installation/) 
instalado em sua máquina, além do PyMongo é claro.

Para verificar se o PyMongo já está instalado em sua máquina você rodar o comando:

```python
import pymongo
```

Já, para verificar se o MongoDB está instalado:

```bash
$ mongod
```
