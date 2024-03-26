# Ponderada_S7

## Codigo rodando 
Imagens com o codigo rodando:
<img src="./Assets/Captura de tela de 2024-03-25 18-11-10.png"> </img>
<img src="./Assets/Captura de tela de 2024-03-25 18-16-50.png"> </img>

## Prometheus:

<img src="./Assets/Captura de tela de 2024-03-25 18-27-26.png"></img>
<img src="./Assets/Captura de tela de 2024-03-25 21-21-49.png"></img>

### Conclusao:
Após ajustar o Prometheus para a supervisão da aplicação Web.API.Track, notamos uma captação de indicadores eficaz e minuciosa. A aplicação, operando no localhost:5244, disponibiliza indicadores de duração de resposta e volume de pedidos, cruciais para o exame da performance e estabilidade do sistema. Os indicadores de histograma referentes ao tempo de processamento HTTP apresentam uma distribuição das latências, enquanto o marcador de cumprimentos revela um entendimento claro do uso do ponto de acesso de cumprimentos. A plataforma do Prometheus facilita a observação desses indicadores ao longo do tempo, proporcionando um recurso indispensável para a avaliação e melhoria constante.

## Tecnologia
Aprofundar-se na monitoração de aplicativos .NET utilizando o OpenTelemetry revela insights detalhados sobre a eficácia e a saúde dos sistemas, viabilizando uma abordagem antecipada para identificar falhas. O OpenTelemetry representa uma norma consolidada na aquisição de dados de telemetria, facilitando a sincronização com plataformas de APM, com destaque para o uso do Prometheus na captura e sumarização de informações e o Grafana para a exibição e elaboração de painéis de controle.

A eficiência do Prometheus é notória na sua habilidade para angariar, reter e analisar informações de forma instantânea.

## Aprendizado

Descobri a relevância fundamental dos três alicerces da monitoração: registros, informações quantitativas e seguimento de atividades distribuídas. Compreendi o papel do OpenTelemetry como um modelo universal para o registro e transmissão de informações de telemetria, promovendo uma fácil integração com plataformas de APM como Prometheus, Grafana e Jaeger. Na aplicação prática, efetuei a configuração de uma aplicação .NET para a emissão de dados quantitativos e registros, empreguei o Prometheus na obtenção dessas informações. Essa experiência sublinhou a significância da monitoração na análise e resolução de questões em ambientes de produção.
