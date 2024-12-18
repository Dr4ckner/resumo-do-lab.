# resumo-do-lab.

Os serviços funcionam com computação, rede e armazenamento. Dentro disso temos as diversas variantes de servidores. Dentre ela temos a nuvem publica, nuvem privada e a nuvem hibrida.
## Nuvem Privada
-> As organizações ficam responsáveis por todo e qualquer tipo de recurso e segurança na empresa.
-> Se necessária atualização ou manutenção. Isso fica na mão da organização.

## Nuvem Publica

-> Não possui nenhuma despesa em escalar o servidor verticalmente.
-> Os aplicativos são provisionados e desprovisionados a hora que quiser.
-> As organizações pagam pelo uso, e apenas por ele.

## Nuvem Hibrida

-> Mistura um pouco das duas nuvens, a publica e a privada.
-> Fornece maior flexibilidade. As organizações controlam a segurança a conformidade e os requisitos.
-> As organizações definem onde executar os aplicativos.

## Despesas de Capital (CapEX)

-> Possui gasto inicial de dinheiro em infraestrutura física.
-> As despesas tem o valor que reduz com o tempo.

## Despesas Operacionais (OpEX)

-> Gasto com produtos e serviços conforme necessário. Pagamento conforme o uso.
-> Recebe cobrança imediatamente.

## Modelo baseado em consumo

-> Previsão mehor de custos.
-> Cada serviço e recurso possui um custo individual.
-> A cobrança é feita com base no seu uso do dia-a-dia.

## Alta disponibilidade

Concentra em manter disponibilidade máxima independente de eventos ou interrupções. Os serviços tem informações contratuais de quanto tempo o serviço pode ficar indisponível.
Você recebe créditos caso passe o limite, você é ressarcido. Caso seja necessário há um suporte que te informa o que está acontecendo. O surpote tem acesso exclusivo por outros meios
para casos de indisponibilidade geral.

## Escalabilidade

-> Refere-se a capacidade de ajustar recursos para atender demandas. Oferece pagamento apenas pelo que está sendo usado. Sendo assim você nunca vai ter um serviço sobrando.

-> Escala vertical - Se você necessita de mais CPU, RAM e coisas relativas a isso, você adiciona por meio da escala vertical a sua máquina virtual.

## Elasticidade

-> Se acontece um salto repentino acentuado (muito grande) na demanda, o ambiente automaticamente é aumentado (podendo ser manualmente também).
-> Se a demanda cair, as máquinas diminuem.

## Confiabilidade

-> Devido ao design descentralizado, a nuvem te da segurança de ter uma infraestrutura confiável e resiliente. Com uma escala global, mesmo que aconteça algum evento
catastrófico em uma região, outra continuará funcionando cobrindo a necessidade.

## Previsibilidade

-> Permite que você avance tranquilamente, ou seja te da informações claras para que consiga melhorar desempenho ou custo.

## Segurança

-> A nuvem te oferece ferramentas de segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e os softwares instalados isso inclui
patches e atualizações (manutenções em geral).

## Governança

-> Dependendo do modelo de operação, as atualizações podem ser feitas automaticamente. Ajuda na governança e na segurança. É necessário uma área para cuidar apenas disso (pelo menos na maior parte das empresas).

## Gerenciabilidade

-> Escala automaticamente, as implementações são feitas com base na necessidade. Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.

### SLA -> ACORDO DE NÍVEL DE SERVIÇO.

Porcentagem entregue pela empresa em relação a qualidade. A microsoft tem algumas porcentagens e isso dita o tempo que o serviço pode ficar indisponível: 99%, 99.9%, 99.95%, 99.99%, 99.999%

O que garante tempos de indisponibilidade de 3,65 dias por ano até 5,26 minutos por ano.

Quando a máquina é gerada pela pessoa / empresa a microsoft não tem nenhuma responsabilidade.

## IaaS, PaaS e SaaS

IaaS - Infraestrutura como serviço

Tendem a ser a área que você como cliente tem mais acesso as informações gerais e também a linha final.
Plataforma conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.

PaaS - Plataforma como serviço

Tem tudo que o IaaS possui, mas com alguns acréscimos. Como sistemas operacionais e ferramentas para desenvolvedores, análise de negócios de gerenciamento de database. Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software.

SaaS - Software como serviço

Conta com Aplicativos/apps hospedados. Temos um exemplo do Microsoft365 que é um grupo de aplicativos que nos disponibiliza softwares e aplicações que já existem e estão prontos. O que muda são as licenças.

## Modelo de responsabilidade compartilhada

Servidor físico -> Responsabilidade completamente do cliente

IaaS -> Hosts físicos, rede física e datacenter físico pela microsoft, todo o resto pelo cliente.

PaaS -> Todos os de cima + Sistema operacional pela conta da Microsoft. O resto é "meio a meio", Controles de rede, aplicativos e infraestrutura de identidade e diretório.

SaaS -> Por outro lado os serviços que antes eram meio a meio ficam por conta da Microsoft, como Controles de rede e aplicativos. Menos Infraestrutura de identidade e diretório. Que fica com a responsabilidade ainda dividida. Informações e dados, dispositivos e contas e identidades ficam por conta do cliente em todas as nuvens.

Quanto mais gestão por parte da Microsoft mais caro o serviço irá ser.

IaaS é mais flexível. Paas é focado em desenvolvimento de aplicativos. SaaS é modelo de preço de pagamento conforme uso. Você paga por software, que utilizam em modelo de assinatura.
