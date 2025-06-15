# Criando máquinas Virtuais na Azure

## Resumo

"Quanto mais 9, menos tempo indisponível o recurso terá"

| Objetivo | Não conformidade por semana | Não conformidade por mês | Não conformidade por ano |
|----------|-----------------------------|--------------------------|--------------------------|
| 99%      | 1,68 hora                   | 7.20 hora                | 3,65 dias                |
| 99,90%   | 10.10 minutos               | 43.20 minutos            | 8,76 horas               |
| 99,95%   | 5 minutos                   | 21.60 minutos            | 4,38 horas               |
| 99,99%   | 1,01 minuto                 | 4,32 minutos             | 52,56 minutos            |
| 99,999%  | 6 segundos                  | 25,90 segundos           | 5,26 minutos             |

As zonas de disponibilidade do Azure são datacenters fisicamente e logicamente separados dentro de uma região, proporcionando alta disponibilidade para aplicações 
e dados críticos.

Em contas de armazenamento do Azure, a redundância refere-se à replicação dos seus dados para garantir alta disponibilidade e durabilidade. 
Existem diferentes tipos de redundância, cada um com suas características e níveis de proteção. 

O armazenamento com redundância local (LRS) é o mais básico, replicando dados três vezes no mesmo local físico. 
O armazenamento com redundância de zona (ZRS) replica dados em três zonas de disponibilidade na mesma região. 
Já o armazenamento com redundância geográfica (GRS) replica dados para uma região secundária, oferecendo proteção contra interrupções regionais. 
O armazenamento geozonal redundante (GZRS) combina a redundância de zona e geográfica, oferecendo o mais alto nível de proteção e disponibilidade. 
