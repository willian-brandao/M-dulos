<img width="412" height="519" alt="image" src="https://github.com/user-attachments/assets/8cee9291-d373-49d4-ba93-4e13d60389fd" />

## Módulos ópticos (parte superior)

Esses são transceptores, usados em switches, roteadores e OLTs:

1.1G SFP SR
* 1 Gb/s
* Fibra multimodo (MM)
* Curta distância (até ~550 m)

2.1G SFP LR
* 1 Gb/s
* Fibra monomodo (SM)
* Longa distância (até ~10 km)

3.10/25G SFP+ SR
* 10 ou 25 Gb/s
* Multimodo
* Curta distância

4.1G SFP to UTP
* Converte fibra para cabo de cobre (RJ-45)

5.100G QSFP28 SR
* 100 Gb/s
* Multimodo
* Datacenters

6.100G QSFP28 LR
* 100 Gb/s
* Monomodo
* Longa distância

7.100G QSFP28 to UTP
* Converte 100G para Ethernet cobre

8.400G QSFP-DD SR/LR
* 400 Gb/s
* Muito usado em backbone e DCs modernos

## Cabos e conectores (parte inferior)

Aqui aparecem os tipos de conectores de fibra:

* LC Duplex

Conector pequeno e muito comum

Usado em SFP, SFP+, QSFP (via breakout)

Fibra SM ou MM

* MPO / MTP

Conector multifibra (8, 12 ou mais fibras)

Usado em 40G, 100G, 400G

Ideal para alta densidade

* Identificação por cor

Aqua → Multimodo OM3 / OM4

Lime-Green → Multimodo OM5

APC Polished (verde) → Monomodo com polimento angular

MTP/MPO-12 ou MPO-8 → quantidade de fibras

* Resumo rápido
Velocidade	Módulo comum	Conector
1G	SFP	LC
10G/25G	SFP+	LC
100G	QSFP28	LC ou MPO
400G	QSFP-DD	MPO

* MÓDULOS ÓPTICOS (TRANSCEPTORS)
* 1G SFP SR

O que é:
Módulo SFP de 1 Gigabit para curta distância.

Características:

Velocidade: 1 Gb/s

Fibra: Multimodo (MM)

Comprimento de onda: 850 nm

Alcance típico:

OM2: até 275 m

OM3/OM4: até 550 m

Conector: LC duplex

Uso comum:

Switches de acesso

Ambientes internos

Datacenters pequenos

* 1G SFP LR

O que é:
Módulo SFP de 1 Gigabit para longa distância.

Características:

Velocidade: 1 Gb/s

Fibra: Monomodo (SM)

Comprimento de onda: 1310 nm

Alcance típico: até 10 km

Conector: LC duplex

Uso comum:

Backbones de ISP

Interligação entre prédios

Redes FTTH (uplinks de OLT)

* 10G / 25G SFP+ SR

O que é:
Módulo SFP+ (10G) ou SFP28 (25G) para curta distância.

Características:

Velocidade: 10 ou 25 Gb/s

Fibra: Multimodo

Comprimento de onda: 850 nm

Alcance:

10G: até 400 m

25G: até 100 m

Conector: LC duplex

Uso comum:

Switches de agregação

Datacenters

Conexão entre servidores

* 1G SFP to UTP

O que é:
SFP que converte fibra para cabo de cobre (RJ-45).

Características:

Velocidade: 1 Gb/s

Meio: Cabo Ethernet (Cat5e/Cat6)

Alcance: até 100 m

Conector: RJ-45

Uso comum:

Converter porta SFP em porta Ethernet

Ambientes onde não há fibra

Equipamentos legados

## Observação: consome mais energia e gera mais calor.

* 100G QSFP28 SR

O que é:
Módulo 100 Gigabit para curta distância.

Características:

Velocidade: 100 Gb/s

Fibra: Multimodo

Comprimento de onda: 850 nm

Alcance: até 100 m

Conectores:

MPO (8 ou 12 fibras)

ou LC (via breakout)

Uso comum:

Datacenters

Interligação de switches core

* 100G QSFP28 LR

O que é:
Módulo 100 Gigabit para longa distância.

Características:

Velocidade: 100 Gb/s

Fibra: Monomodo

Comprimento de onda: 1310 nm

Alcance: até 10 km

Conector: LC duplex

Uso comum:

Backbone de ISP

Core de rede

Interligação de DCs

* 100G QSFP28 to UTP

O que é:
Converte uma porta QSFP28 em Ethernet cobre.

Características:

Velocidade: 100 Gb/s

Conector: RJ-45

Uso bem específico

## Pouco comum, alto consumo e custo elevado.

* 400G QSFP-DD SR / LR

O que é:
Módulo de 400 Gigabit (QSFP Double Density).

Características:

Velocidade: 400 Gb/s

Fibra:

SR → Multimodo

LR → Monomodo

Conector: MPO

Uso avançado

Uso comum:

Datacenters hyperscale

Backbones de alta capacidade

Operadoras grandes

* CONECTORES E CABOS
* LC Duplex

Conector padrão atual

Usa 2 fibras (TX/RX)

Compatível com SFP, SFP+, QSFP (via breakout)

Muito usado em ISP e FTTH

* MPO / MTP

Conector multifibra

Pode ter:

8 fibras

12 fibras

Necessário para 40G, 100G, 400G

Alta densidade e alto desempenho

* Cores dos conectores

Aqua → Multimodo OM3 / OM4

Lime-Green → Multimodo OM5

Verde (APC) → Monomodo com menor reflexão

* RELAÇÃO COM GPON / FTTH (importante para você)

No dia a dia de ISP / FTTH, os mais usados são:

1G SFP LR → uplinks antigos

10G SFP+ LR → uplinks modernos

25G SFP28 LR → OLTs XGS-PON

100G QSFP28 LR → backbone / core
