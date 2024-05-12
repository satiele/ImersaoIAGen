**Chatbot de Planejamento de Viagens com Gemini Pro** <br>
Este chatbot utiliza o poder do modelo de linguagem Gemini Pro do Google AI para auxiliar no planejamento de viagens de férias personalizadas. Com base nas informações fornecidas pelo usuário, o chatbot gera roteiros detalhados que incluem sugestões de destinos, pontos turísticos, dicas de bagagem, previsão do tempo e estimativas de custos.<br><br>
**Funcionalidades**<br>
*Personalização: O chatbot coleta informações detalhadas sobre a viagem desejada, incluindo:<br>
*Preferência por viagens nacionais ou internacionais<br>
*Duração da viagem (em dias)<br>
*Mês da viagem<br>
*Número de pessoas<br>
*Orçamento total<br>
*Cidade de origem<br><br>
*Possibilidade de visitar múltiplos destinos<br>
Geração de Roteiro Otimizado: O chatbot gera um roteiro otimizado, considerando:<br>
Divisão equilibrada dos dias entre os destinos, levando em conta o tempo de deslocamento<br>
Viabilidade dos destinos em relação ao orçamento, duração da viagem e localização<br><br>
Informações detalhadas sobre cada destino, incluindo:<br>
*Principais pontos turísticos<br>
*Dicas de itens para levar na mala, de acordo com o clima e as atividades<br>
*Previsão geral do tempo<br>
*Orçamento detalhado com estimativas de custos para:<br>
*Transporte (considerando a cidade de origem e deslocamentos entre destinos)<br>
*Passeios turísticos<br>
*Refeições (café da manhã, almoço e jantar)<br>
*Hospedagem (considerando o número de pessoas)<br>
Exclusão de Destinos Conhecidos: O chatbot permite que o usuário informe se já conhece algum dos destinos sugeridos e, em caso afirmativo, exclui esses destinos e gera novas sugestões.<br>
Interação Contínua: O chatbot continua interagindo com o usuário, fornecendo novas sugestões de roteiro até que ele esteja satisfeito com as opções.<br>
<br>
Como Utilizar<br>
Instalação:<br>
Certifique-se de ter o Python instalado em seu sistema.<br>
Instale a biblioteca google-generativeai utilizando o comando:<br>
pip install --upgrade google-generativeai<br>
Configuração:<br>
Obtenha uma chave de API do Google AI para o Gemini Pro.<br>
Substitua "SUA_API_KEY" no código pela sua chave de API real<br>:
GOOGLE_API_KEY = "SUA_API_KEY" <br>
genai.configure(api_key=GOOGLE_API_KEY)<br>
<br>
Execução:<br>
Execute o script Python.<br>
Responda às perguntas do chatbot para fornecer as informações sobre a sua viagem.<br>
O chatbot irá gerar um roteiro detalhado e personalizado com base nas suas respostas.<br><br>
Observações<br>
O Gemini Pro é um modelo de linguagem em constante desenvolvimento, portanto, a qualidade das respostas pode variar.<br>
As estimativas de custo são aproximações e podem não refletir os preços reais. É recomendável consultar fontes confiáveis para obter informações atualizadas sobre custos de viagem.<br>
O chatbot foi desenvolvido para fins educacionais e de demonstração. Ele não deve ser considerado como um substituto para o planejamento profissional de viagens.<br><br>
Próximos Passos<br>
Integrar o chatbot com APIs de viagens reais para obter informações mais precisas sobre preços e disponibilidade.<br>
Permitir que o usuário refine a pesquisa, escolhendo um destino específico ou definindo filtros adicionais.<br>
Implementar recursos de interface gráfica para uma experiência de usuário mais amigável.<br>
