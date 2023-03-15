---
id: 6
type: computerScienceCollegeProjects
title: APS 6 Sistemas Operacionais
image: https://user-images.githubusercontent.com/62115215/208798426-0b528230-530f-446f-9c1e-04df1b18835d.png
description: Projeto APS do 6º semestre de Ciência da Computação
date: 1654007218000
github:
tags: [java]
slug: aps-6
---

# APS 6º Semestre

## Introdução

APS (Atividades Práticas Supervisionadas) é um projeto de final de semestre que precisava fazer na faculdade, ou seja, esse projeto foi feito na metade pro fim do sexto semestre das minhas aulas de Ciência da Computação.

Naquele semestre, a matéria principal estudada foi sistemas operacionais, por isso, o projeto deveria ser criar uma simulação de como um sistema de backup em Linux funcionaria utilizando 3 ou mais máquinas virtuais, elas deveriam estar conectadas, assim fazendo redundância de backup dos arquivos

## Sobre

Esse é um projeto desenvolvido para fazer backup de comandas de um restaurante. Nele temos 3 máquinas virtuais (Caixa, Server e Administrador), e eles estão conectados na mesma rede.

Como é uma simulação, o `Caixa` tem um script em Python que gera comandas aleatórias em tempos aleatórios entre 12h e 15h (Possível horário de funcionamento do caixa).

Entre 15h e 15h10, será gerado um backup diário e mandado para o server

Às 15h15 será um relatório das comandas e mandado para o servidor

Entre 15h20 e 15h25, será feito um relatório do que aconteceu no dia para a máquina administrador

Cada máquina tem um firewall cadastrado, por isso, o caixa não consegue se comunicar com o administrador
Além disso, um proxy configurado baseado no papel de cada máquina

## Gifs, Imagens e Vídeos
