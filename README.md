# AnnA One — Projetos Escolares

**Registro de funcionalidades e situação do projeto**

- **Revisão:** 19/10/2026
- **Responsável:** Elison Borges
- **Repositório:** [elisonborges/annaone-projetos-escolares](https://github.com/elisonborges/annaone-projetos-escolares)
- **Plataforma:** GitHub Pages + Supabase

## 1. Objetivo

O AnnA One — Projetos Escolares é uma aplicação educacional destinada ao recebimento, acompanhamento, avaliação e publicação de trabalhos escolares em PDF, incluindo e-books produzidos pelos estudantes.

O sistema separa a entrega do aluno, a avaliação do professor, a administração e a publicação na Biblioteca Digital.

## 2. Módulos implementados

| Módulo | Funcionalidades | Situação |
| --- | --- | --- |
| [Página inicial](https://elisonborges.github.io/annaone-projetos-escolares/) | Navegação entre módulos | Implementado |
| [Entrega](https://elisonborges.github.io/annaone-projetos-escolares/entrega/) | Identificação do grupo, projeto e envio de PDF | Validado |
| Comprovante | Protocolo, código de acesso, impressão e PDF | Validado |
| [Consulta](https://elisonborges.github.io/annaone-projetos-escolares/consulta/) | Acompanhamento, orientações e reenvio | Validado |
| [Professor](https://elisonborges.github.io/annaone-projetos-escolares/professor/) | Análise, orientações, aprovação e relatórios | Validado |
| [Administração](https://elisonborges.github.io/annaone-projetos-escolares/admin/) | Interface administrativa e recursos de gestão | Implementado; validação integral não documentada |
| [Biblioteca Digital](https://elisonborges.github.io/annaone-projetos-escolares/biblioteca/) | Obras publicadas, capas e ficha do e-book | Implementado; melhorias visuais aprovadas |
| Leitor | Leitura de e-books publicados | Implementado |

## 3. Fluxo pedagógico

1. O aluno seleciona o projeto e identifica seu grupo.
2. Envia o e-book em PDF.
3. Recebe protocolo e código de acesso.
4. O professor analisa o trabalho.
5. O professor pode solicitar correções ou aprovar a entrega.
6. O aluno acompanha a avaliação e pode reenviar o PDF quando solicitado.
7. A publicação na Biblioteca Digital ocorre separadamente da aprovação.

**Importante:** aprovação não implica publicação automática.

O fluxo de entrega, correção, reenvio e aprovação já foi validado com dados fictícios. Não é necessário repetir esses testes sem alteração funcional relevante.

## 4. Melhorias aprovadas

- Orientações compactas na página de entrega.
- Informação dinâmica do limite de tamanho do PDF.
- Mensagens explicativas na consulta do aluno.
- Orientações para correções no painel do professor.
- Confirmação antes da aprovação.
- Mensagem de sucesso após a avaliação.
- Padronização de direitos autorais nas páginas e impressos.
- Ampliação das capas dos e-books.
- Ficha detalhada das obras na Biblioteca Digital.

## 5. Infraestrutura

- **GitHub Pages:** hospedagem das interfaces.
- **Supabase:** autenticação, banco de dados, armazenamento e funções de processamento.
- **Resend:** serviço de envio de e-mails.

Na revisão de 19/10/2026, as 12 Edge Functions consultadas estavam ativas. Esse status, isoladamente, não comprova o funcionamento de cada integração.

## 6. Situação dos dados

Na consulta de 19/10/2026, havia quatro trabalhos registrados:

- Três aguardando avaliação.
- Um em análise.

Os dados reais devem ser preservados. Arquivos antigos mantidos no Storage por decisão do responsável não devem ser excluídos automaticamente.

## 7. Pendências e verificações futuras

### Documentação
- Manter o README atualizado.
- Registrar versões e alterações aprovadas.

### Verificações condicionais
- Validar a ficha detalhada quando houver uma publicação real autorizada.
- Confirmar o funcionamento integral do painel administrativo, caso ainda não exista registro de validação.
- Verificar a situação do backup completo do banco antes de mudanças estruturais.

### Sem necessidade de retrabalho
- Fluxo de entrega e comprovante.
- Consulta e reenvio.
- Avaliação e aprovação.
- Melhorias visuais já aprovadas.

## 8. Regras de manutenção

1. Preservar funcionalidades e dados existentes.
2. Verificar o código antes de propor alterações.
3. Evitar repetir testes já concluídos.
4. Criar demonstrações somente quando necessárias.
5. Não publicar alterações sem aprovação.
6. Registrar mudanças e versões.
7. Priorizar soluções estáveis, gratuitas e de manutenção simples.

---

**Estado da documentação:** versão inicial aprovada em 19/10/2026.  
**Escopo desta atualização:** somente README.md; nenhuma mudança nas páginas, no banco ou nas funções.
