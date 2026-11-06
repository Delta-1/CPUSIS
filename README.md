# CPUSIS Hub

O ecossistema que guia o seu negócio.

Aplicação responsiva em um único `index.html`, com HTML, CSS e JavaScript incorporados. Sem instalação de dependências, frameworks ou chamadas de terceiros para carregar a interface. Os ícones de interface são derivados do Lucide (licença ISC).

## Explorar

- Site institucional com soluções ERP, PDV e automação comercial, apresentação da empresa, suporte e treinamentos.
- Alternância entre tema claro e escuro, com preferência local.
- Login de demonstração: **cliente.demo** / **cpusis123**. Também é possível entrar pelo botão **Conhecer a demonstração**.
- Painel Principal, Meus Downloads, Financeiro, Suporte Técnico, Treinamentos, Área do Colaborador e Configurações.
- Chamados locais com assunto, sistema, prioridade, descrição, filtros e encerramento.
- Três guias interativos, com progresso salvo no navegador.
- Perfil, checklist, anotações e preferências locais.
- Exportação de faturas fictícias em CSV e dos dados locais em JSON; impressão de fatura demonstrativa.
- Navegação mobile, atalhos por hash e janelas acessíveis pelo teclado.

## Limites desta etapa

O banco de dados foi deixado para depois, conforme solicitado. O login **não autentica usuários reais**. Não existe isolamento seguro entre contas, sincronização entre aparelhos, envio real de chamados ou recuperação de senha por e-mail. Não armazene informações sensíveis na demonstração.

PIX, boleto, valores, vencimentos e status financeiros são **fictícios, sem validade para pagamento**. O desenho do código e o texto para copiar não representam um PIX pagável. Não são geradas cobranças.

Os instaladores Windows/Android e links iOS ainda não foram fornecidos. O catálogo identifica essa situação; não distribui instaladores fictícios. Os vídeos oficiais poderão ser adicionados posteriormente; os guias textuais interativos já funcionam.

## Publicação

GitHub Pages: selecionar **Settings → Pages → Deploy from a branch → main → / (root)**. A entrada é `index.html`, e não o README. Endereço padrão: https://delta-1.github.io/CPUSIS/

O arquivo também pode ser servido por qualquer servidor estático. Não exige compilação. Rotas usam hash (`#home`, `#login`, `#hub/overview`) para funcionar no GitHub Pages sem reescritas.

## Validação

JavaScript verificado sintaticamente. Fluxos de acesso de demonstração, criação/encerramento de chamados, avanço/conclusão e persistência de guias, simulação PIX, edição/persistência de perfil e navegação no celular conferidos na interface. Layout mobile verificado em uma área de 390 × 844 px.

## Próxima etapa

Conectar autenticação e banco, definir permissões e segregação por empresa, integrar cobranças oficiais, vincular instaladores e materiais de treinamento e conectar o atendimento real.
