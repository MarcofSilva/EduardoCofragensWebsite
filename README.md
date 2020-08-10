# EduardoCofragens Website

Hugo theme [Now UI](https://github.com/cboettig/hugo-now-ui/) was used as template.

# TODO deixar tudo em ordem em relação a licensas copyrights e critério ao autor do template usado
# TODO mini icon change
# TODO meta tags do site (<head>)
# TODO SEO
# TODO explicar: estruta de pastas para fotos de portefolio, como e onde adicionar snippets de codigo para expandir o portefolio (incluir aqui os pedaços de codigo a alterar e acrescentar)

# TODO cenas em content apenas se forem seccoes mesmo...se por exemplo contactor e assim nao forem ter uma pagina proprio por essas informacoes em data
# TODO see the information that pai quer ter por obbra no portofolio para a receber a toda no .md e formatar sempre da mesma forma (neste momento é escrever no title como vai aparecer)

.Sites.Pages section
.Sites.RegularPages items in section
.permalink link to a specific item

Use images with the following resolution ...
Use videos with the following resolution ...´

config.toml hugo configuration
nav.html for top bar
footer.html for footer
_index.html for homepage content
index.html for homepage template
index_baseof.html for homepage header
baseof.html for secundarypages header

CNAME contains the custom domain and is stored under static, so that after each build it will be available in the gh-pages branch that has the static files of the website

workflow hugo build & deploy generates the new static files after every push to the master branch
