# Canudo - Gerador Portátil de Certificados 🎓

O **Canudo** é uma ferramenta estática, leve e ultra-acessível desenvolvida para professores, palestrantes e criadores de conteúdo que precisam emitir certificados de cursos livres em lote diretamente pelo celular, sem complicações, sem servidores e com total autonomia.

O nome brinca com o apelido carinhoso dado ao diploma no Brasil. O projeto resolve um problema real de gerenciamento e acessibilidade: a dor de cabeça de gerar múltiplos documentos em PDF no ambiente mobile, garantindo que o resultado final saia perfeitamente diagramado e com a validade jurídica necessária para o mercado e atividades extracurriculares acadêmicas.

---

## 🔥 Recursos Principais

* **Persistência Local Automática:** Nunca perca seus dados por fechamentos acidentais do navegador. As informações do curso e a lista de alunos são salvas em tempo real no `localStorage` do dispositivo móvel.
* **Entrada de Dados em Lote:** Esqueça o trabalho de preencher um formulário por aluno. Basta colar a lista de estudantes de uma vez só (um por linha no formato `Nome - Documento`) e o sistema cria a mesa de operação automaticamente.
* **Mesa de Emissão Individual (Fila de Cliques):** Uma lista totalmente otimizada para leitores de tela com botões semânticos individuais. Você gera o PDF limpo e isolado de cada aluno com um único clique, facilitando o envio direto via WhatsApp ou e-mail.
* **Assinatura Cursiva Dinâmica (CSS Puro):** Não precisa caçar arquivos de imagem ou fotos de assinaturas no celular. O sistema importa uma fonte caligráfica elegante e "desenha" o autógrafo baseado no nome do instrutor digitado, mantendo o elemento como texto acessível.
* **Diagramação Completa (Frente e Verso):** Cada emissão gera duas páginas automáticas no motor de impressão:
    * *Frente:* O certificado tradicional com bordas, textos centralizados e a chancela do instrutor.
    * *Verso:* O conteúdo programático completo e os metadados de amparo legal.
* **Validade Institucional Automatizada:** O verso do documento já nasce com as referências à legislação brasileira de Cursos Livres (Lei nº 9.394/96 - LDB e Decreto Presidencial nº 5.154/04) e gera uma chave única de autenticidade (`UUID`) por documento.

---

## 🛠️ Como Executar o Projeto

Por ser uma aplicação de arquivo único (*Single-File Application*), o funcionamento é 100% offline e independente:

1. Baixe o arquivo `index.html` deste repositório.
2. Abra o arquivo diretamente em qualquer navegador do seu computador ou celular.
3. Se preferir, ele está hospedado e pronto para uso no **GitHub Pages** deste repositório.

---

## 🤝 Filosofia de Desenvolvimento & Acessibilidade

O **Canudo** foi construído sob rigorosos padrões de acessibilidade web. Estrutura semântica nativa, gerenciamento de foco controlado e marcações dinâmicas para leitores de tela (`aria-live`) garantem que usuários cegos ou com baixa visão operem a mesa de emissão com total independência, privacidade e agilidade. Uma ferramenta feita para democratizar o ensino e a entrega de credenciais, livre de barreiras capacitistas.

---

## 📬 Contato e Feedback

Gostou do projeto, encontrou algum comportamento inesperado ou quer sugerir uma evolução? Este software faz parte do meu portfólio de soluções independentes e seu feedback é muito bem-vindo!

* **E-mail:** [euconcego@gmail.com](mailto:euconcego@gmail.com)

---

Desenvolvido com 💻 por **Anderson Carvalho**
