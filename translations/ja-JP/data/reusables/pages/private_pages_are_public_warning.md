  {% warning %}

  **Warning**: {% if enterpriseServerVersions contains currentVersion or currentVersion == "github-ae@latest" %}If your site administrator has enabled Public Pages, {% endif %}{% data variables.product.prodname_pages %} sites are publicly available on the internet, even if the repository for the site is private{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.19" or currentVersion == "github-ae@latest" %} or internal{% endif %}. サイトのリポジトリにセンシティブなデータがあるなら、公開前にそれを取り除くのが良いでしょう。 For more information, see{% if enterpriseServerVersions contains currentVersion or currentVersion == "github-ae@latest" %} "[Configuring {% data variables.product.prodname_pages %} for your enterprise](/admin/configuration/configuring-github-pages-for-your-enterprise#enabling-public-sites-for-github-pages)" and{% endif %} "[About repository visibility](/github/creating-cloning-and-archiving-repositories/about-repository-visibility)."

  {% endwarning %}
