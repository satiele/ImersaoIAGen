Chatbot de Planejamento de Viagens com Gemini Pro
Este chatbot utiliza o poder do modelo de linguagem Gemini Pro do Google AI para auxiliar no planejamento de viagens de férias personalizadas. Com base nas informações fornecidas pelo usuário, o chatbot gera roteiros detalhados que incluem sugestões de destinos, pontos turísticos, dicas de bagagem, previsão do tempo e estimativas de custos.
Funcionalidades
Personalização: O chatbot coleta informações detalhadas sobre a viagem desejada, incluindo:
Preferência por viagens nacionais ou internacionais
Duração da viagem (em dias)
Mês da viagem
Número de pessoas
Orçamento total
Cidade de origem
Possibilidade de visitar múltiplos destinos
Geração de Roteiro Otimizado: O chatbot gera um roteiro otimizado, considerando:
Divisão equilibrada dos dias entre os destinos, levando em conta o tempo de deslocamento
Viabilidade dos destinos em relação ao orçamento, duração da viagem e localização
Informações detalhadas sobre cada destino, incluindo:
Principais pontos turísticos
Dicas de itens para levar na mala, de acordo com o clima e as atividades
Previsão geral do tempo
Orçamento detalhado com estimativas de custos para:
Transporte (considerando a cidade de origem e deslocamentos entre destinos)
Passeios turísticos
Refeições (café da manhã, almoço e jantar)
Hospedagem (considerando o número de pessoas)
Exclusão de Destinos Conhecidos: O chatbot permite que o usuário informe se já conhece algum dos destinos sugeridos e, em caso afirmativo, exclui esses destinos e gera novas sugestões.
Interação Contínua: O chatbot continua interagindo com o usuário, fornecendo novas sugestões de roteiro até que ele esteja satisfeito com as opções.
Como Utilizar
Instalação:
Certifique-se de ter o Python instalado em seu sistema.
Instale a biblioteca google-generativeai utilizando o comando:
pip install --upgrade google-generativeai
Use code with caution.
Bash
Configuração:
Obtenha uma chave de API do Google AI para o Gemini Pro.
Substitua "SUA_API_KEY" no código pela sua chave de API real:
GOOGLE_API_KEY = "SUA_API_KEY" 
genai.configure(api_key=GOOGLE_API_KEY)
Use code with caution.
Python
Execução:
Execute o script Python.
Responda às perguntas do chatbot para fornecer as informações sobre a sua viagem.
O chatbot irá gerar um roteiro detalhado e personalizado com base nas suas respostas.
Observações
O Gemini Pro é um modelo de linguagem em constante desenvolvimento, portanto, a qualidade das respostas pode variar.
As estimativas de custo são aproximações e podem não refletir os preços reais. É recomendável consultar fontes confiáveis para obter informações atualizadas sobre custos de viagem.
O chatbot foi desenvolvido para fins educacionais e de demonstração. Ele não deve ser considerado como um substituto para o planejamento profissional de viagens.
Próximos Passos
Integrar o chatbot com APIs de viagens reais para obter informações mais precisas sobre preços e disponibilidade.
Permitir que o usuário refine a pesquisa, escolhendo um destino específico ou definindo filtros adicionais.
Implementar recursos de interface gráfica para uma experiência de usuário mais amigável.
