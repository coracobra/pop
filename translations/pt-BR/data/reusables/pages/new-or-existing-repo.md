Se o seu site for um projeto independente, você pode criar um novo repositório para armazenar o código-fonte do seu site. Se o seu site estiver associado a um projeto existente, você pode adicionar o código-fonte {% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2. 2" or currentVersion == "github-ae@latest" %}a esse repositório do projeto, em uma pasta de `/docs` no branch padrão ou em um branch diferente.{% else %}para o seu site para um branch de `páginas gh-pages` ou uma pasta de `docs` no branch `mestre` no repositório do projeto.{% endif %} Por exemplo, se você estiver criando um site para publicar a documentação de um projeto que já está em {% data variables.product.product_name %}, você deverá armazenar o código-fonte para o site no mesmo repositório do projeto.

{% if currentVersion == "free-pro-team@latest" %}If the account that owns the repository uses {% data variables.product.prodname_free_user %} or {% data variables.product.prodname_free_team %}, the repository must be public.{% endif %}

Se você deseja criar um site em um repositório existente, pule para a seção "[Criar o seu site](#creating-your-site).