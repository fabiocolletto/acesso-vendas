# Acesso ao Vendas

Atalho estático para https://www.5horas.com.br/aplicativos/. O redirecionamento ocorre no navegador,
na mesma aba, preservando consulta e fragmento e sem manipular autenticação.
Não é um redirecionamento HTTP 301/302. Sem JavaScript, o link permite continuar.
O destino é fixo; parâmetros recebidos não escolhem outro servidor.

Domínio: `vendas.5horas.com.br`.
DNS previsto: CNAME `vendas` → `fabiocolletto.github.io`.
Publicação: GitHub Pages, branch `main`, pasta `/`.
HTTPS precisa de DNS válido para emissão do certificado e posterior enforcement.
