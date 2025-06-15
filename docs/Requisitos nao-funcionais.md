
# Requisitos não-funcionais seguindo  a ISO25010

| **Código** | **Nome** | **Descrição** | **Categoria** | **Métricas / Notas** |
| :-: | :-: | :-: | :-:| :-: |
| RNF01 | Facilidade de uso | Os usuários devem ser capazes de encontrar o cardápio da semana em menos de 30s, após o carregamento da página.| Usabilidade| Tempo máximo para encontrar informação: 30 segundos após carregamento. | 
|RNF02 | Design responsivo | O site deve se adaptar a telas mobile, ajustando layout e conteúdo para diferentes tamanhos de tela | Responsividade|  Compatível com telas de dispositivos móveis (smartphones e tablets) | 
|RNF03| Acessibilidade| O site deve oferecer suporte a leitores de tela para garantir acessibilidade a pessoas com deficiência visual| Acessibilidade|  Compatibilidade com os principais leitores de tela (ex: NVDA, JAWS). | 
|RNF04| Acessibilidade| O site deve conter textos alternativos para imagens | Acessibilidade|  100% das imagens devem ter texto alternativo significativo. | 
|RNF05| Resposta a ações| O site deve conter feedbacks visuais para interações do usuário| FeedBack ao usuário|  Feedback visível em até 200ms após a interação do usuário. | 
|RNF06| Suporte a acesso | O site deve suportar alto número de requisições de acesso simultanêos sem perda de performance| Escalibidade| O sistema de suportar pelo menos 200 requisições simultâneas com tempo de resposta menor que 5 segundos|
| RNF07      | Alta disponibilidade | O sistema deve estar disponível para acesso dos usuários pelo menos 99% do tempo, principalmente em horários de refeições. | Confiabilidade   | Uptime mínimo de 99% mensal.                  |
| RNF08      | Segurança de dados   | O sistema deve proteger dados pessoais e alimentares dos usuários, como alergias e preferências, usando autenticação segura e criptografia de dados. | Segurança       | Dados sensíveis criptografados e autenticação obrigatória para ações protegidas. |