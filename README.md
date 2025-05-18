homelessness-aid-multiagent-system
🤝 Um Sistema Multiagente para Apoio e Informação a Pessoas em Situação de Rua
🌟 Sobre o Projeto
Este projeto propõe e desenvolve um Sistema Multiagente (SMA) inovador focado em fornecer informações cruciais e personalizadas para pessoas em situação de rua. Acreditamos que o acesso rápido e preciso a dados sobre abrigos, alimentação, saúde, oportunidades de emprego e outros recursos essenciais pode fazer uma diferença significativa na vida de indivíduos vulneráveis.

O objetivo é criar uma rede inteligente de agentes de software que colaborem para mapear recursos, compreender as necessidades individuais, gerar recomendações eficazes e alertar sobre condições importantes, tudo isso visando auxiliar de forma mais humana e eficiente.

✨ Os Agentes do Sistema
Nosso sistema é composto por quatro agentes principais, cada um com uma função especializada e trabalhando em harmonia:

1. 🗺️ Agente de Mapeamento e Recursos (AMR)
Função: É o "cérebro" de dados do sistema. Responsável por coletar, verificar e manter atualizadas todas as informações sobre recursos e serviços disponíveis em uma determinada localidade (abrigos, restaurantes populares, postos de saúde, oportunidades de emprego, etc.).
Interações: Fornece dados atualizados e filtrados para o Agente de Recomendação e Encaminhamento.
2. 🗣️ Agente de Interação e Necessidades (AIN)
Função: Atua como a interface direta com a pessoa em situação de rua. Ele compreende as necessidades imediatas do indivíduo através de uma interação simplificada (pode ser via totem interativo, aplicativo em celular ou com o auxílio de assistentes sociais).
Interações: Envia as necessidades identificadas para o Agente de Recomendação e Encaminhamento e recebe as recomendações para apresentar ao usuário.
3. 🎯 Agente de Recomendação e Encaminhamento (ARE)
Função: O "matchmaker" do sistema. Recebe as necessidades do usuário e as compara com os recursos disponíveis para encontrar a melhor opção e gerar um encaminhamento personalizado. Considera proximidade, disponibilidade, horários e requisitos específicos.
Interações: Consulta o Agente de Mapeamento e Recursos e envia as recomendações prontas para o Agente de Interação e Necessidades. Pode receber alertas do Agente de Alertas e Clima para priorizar certos recursos.
4. 🚨 Agente de Alertas e Clima (AAC)
Função: Um agente proativo que monitora condições externas e eventos importantes para enviar alertas e informações críticas. Isso inclui previsões de tempo extremas (frio intenso, chuvas fortes), alertas de saúde pública ou eventos beneficentes.
Interações: Pode enviar informações diretamente ao Agente de Interação e Necessidades ou influenciar as prioridades do Agente de Recomendação e Encaminhamento.
🛠️ Como Funciona (Visão Geral)
Uma pessoa em situação de rua interage com o Agente de Interação e Necessidades (AIN), informando suas necessidades (ex: "Preciso de um lugar para dormir hoje à noite").
O AIN envia essa solicitação ao Agente de Recomendação e Encaminhamento (ARE).
O ARE consulta o Agente de Mapeamento e Recursos (AMR) para buscar abrigos disponíveis que correspondam aos critérios (localização, vagas, etc.).
Simultaneamente, o Agente de Alertas e Clima (AAC) pode estar monitorando uma onda de frio, por exemplo, e alerta o ARE para priorizar abrigos com aquecimento.
O ARE processa todas essas informações e gera uma lista de recomendações otimizadas.
O AIN recebe essas recomendações e as apresenta à pessoa de forma clara, com detalhes como endereço, horários e como chegar.
🚀 Tecnologias Utilizadas (Exemplos)
Embora o projeto ainda esteja em fase conceitual para este README, as tecnologias potenciais para a implementação incluem:

Linguagem de Programação: Python (para desenvolvimento dos agentes)
Frameworks Web: Flask / FastAPI (para APIs de comunicação entre agentes)
Banco de Dados: PostgreSQL / MongoDB (para o Agente de Mapeamento e Recursos)
Gerenciamento de Agentes: Plataformas como SPADE ou bibliotecas personalizadas para comunicação e coordenação.
Geolocalização: APIs de mapas (Google Maps API, OpenStreetMap)
Previsão do Tempo: APIs de clima
Interface do Usuário: HTML, CSS, JavaScript (para a interface do AIN, se houver um totem ou app web)
