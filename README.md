# EduardoCofragens Website

Hugo theme [Now UI](https://github.com/cboettig/hugo-now-ui/) was used as template.

# TODO deixar tudo em ordem em relação a licensas copyrights e critério ao autor do template usado
# TODO mini icon change
# TODO meta tags do site (<head>)
# TODO SEO
# TODO explicar: estruta de pastas para fotos de portefolio, como e onde adicionar snippets de codigo para expandir o portefolio (incluir aqui os pedaços de codigo a alterar e acrescentar)

Use images with the following resolution ...
Use videos with the following resolution ...´

config.toml hugo configuration
nav.html for top bar
footer.html for footer
_index.html for homepage content
index.html for homepage template
index_baseof.html for homepage header
baseof.html for secundarypages header

script for generate static files ready for display in github page
mv docs/CNAME .
rm -r docs
hugo -d docs
mv CNAME docs