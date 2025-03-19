# GIT COMMIT SEMÁTICO

__________________________________________________________________
tipo| Quando usar?
------------------------------------------------------------------

feat: Adiciona uma nova funcionalidade
fix: Corrige um bug
docs: Atualiza a documentação
style: Altera apenas formatação, sem impacto no código
perf: Melhora a performace
refactor: Refatora o código sem alterar comportamento
test: Adiciona ou modifica testes
chore: Alteração que não impactam à produção
build: Mudanças de dependências
ci: Alterações de pipelines de automação
revert: Reversão de um commit anterior
security: Correção de vunerabilidades ou melhorias de seguranças
infra: Mudanças na infraestrutura (dockers,...)
hotfix: Correção emergencial em produção
deprecate: Funcionalidades absoletas
___________________________________________________________________

Exemplo práticos:

git commit -m "feat: Adiciona opção de login com google"
git commit -m "fix: corrige erro de validação no cadastro"
git commit -m "docs: atualiza README com instruções de deploy"
git commit -m "style: Aplica formatação consistente ao arquivo de configuração"
git commit -m "perf: Otimiza consulta ao banco de dados para listagem de produtos"
git commit -m "refactor: Extrai lógica de validação de e-mail para uma função separada"
git commit -m "test: Adiciona testes unitários para o componente de autenticação de usuários"
git commit -m "chore: Atualiza dependência do ladash para a versão mais recente"
git commit -m "build: Adiciona script para build da aplicação em ambiente de produção"
git commit -m "ci: Corrige falha no pipeline de deploy para o ambiente de staging"
git commit -m "revert: Reverte commit  'feat: Implementa sistema de autenticação com OAuth2' devido a problemas de seguranças."
git commit -m "security: Corrige vulnerabilidade de XSS na página de perfil do usuário."
git commit -m "infra: Migra configuração de banco de dados para o novo cluster Docker"
git commit -m "hotfix: Corrige erro que impede usuários de finalizar a compra"
git commit -m "deprecate: Marca funcionalidade de 'compartilhamento por e-mail' como absoleta"
