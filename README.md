<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a8e6cf,100:1b7f4b&height=200&section=header&text=Sophia%20Moura&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Analista%20de%20Dados&descSize=18&descAlignY=58&animation=none" width="100%"/>

Sou graduanda de Ciência da Computação com foco em Análise de Dados, apaixonada por transformar informação em decisão.

<a href="https://www.linkedin.com/in/sophia-moura-b41308265/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-1B7F4B?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="" target="_blank">
  <img src="https://img.shields.io/badge/Portf%C3%B3lio-2E9E63?style=for-the-badge&logo=googlechrome&logoColor=white" />
</a>
<a href="mailto:sopphiamguedes@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-4CB782?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

## Linguagens e Tecnologias

<p align="left">
  <img src="https://img.shields.io/badge/SQL-1B7F4B?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/Git-2E9E63?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Python-4CB782?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/R-1B7F4B?style=for-the-badge&logo=r&logoColor=white" alt="R"/>
  <img src="https://img.shields.io/badge/DAX-2E9E63?style=for-the-badge&logoColor=white" alt="DAX"/>
</p>

## Contato

📫 sopphiamguedes@gmail.com &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/sophia-moura-b41308265/)
## Projetos

**[Tradutor de Libras em tempo real](https://github.com/sophia-moura/)** · Visão computacional

Reconhece o alfabeto manual de Libras pela webcam e escreve o texto na tela. Coletei e rotulei 9.271 amostras de 20 letras. Validei com `LeaveOneGroupOut` por sessão de captura, e não por sorteio: cada dobra testa o modelo numa condição de luz e de posição que ele nunca viu. Reporto **88,4%**, e não a média de 95,9%, porque as dobras antigas tinham só 5 letras e inflavam o resultado. O sistema recusa a resposta quando não reconhece o que vê. São 104 testes e 21 decisões de arquitetura escritas.

`Python` `OpenCV` `MediaPipe` `scikit-learn` `PyTorch` `pytest`

**[Assistente de análise de dados com IA](https://github.com/dudamarqs/ai-data-scientist)** · LLM aplicado · [aplicação no ar](https://ai-data-scientist-6gl8.onrender.com)

Você sobe um CSV e pergunta em português. O LLM escolhe a ferramenta, mas quem calcula é o Python: pandas, scikit-learn e SHAP. Cada resposta mostra qual ferramenta foi chamada e qual número voltou — nenhum valor sai do modelo de linguagem. O provedor troca entre Gemini e Claude por uma linha do `.env`. São 51 testes, Docker Compose e CI, porque para mim um sistema só fica pronto quando outra pessoa consegue rodar.

`Python` `FastAPI` `pandas` `scikit-learn` `SHAP` `Docker` `PostgreSQL` `GitHub Actions`

**[Análise SQL de 100 mil pedidos](https://github.com/dudamarqs/olist-ecommerce-analysis)** · SQL e estatística

Dez perguntas de negócio sobre pedidos reais do marketplace Olist, cada uma com a ressalva junto do número. **Dois dos dez achados não sobreviveram a um teste de permutação** — e estão publicados assim mesmo, porque é isso que uma análise honesta parece.
