# Litoral Arretado

Landing page estática em português para passeios em Japaratinga, Alagoas.

URL de produção pretendida: https://dabaphira.com.br/litoral-arretado/
Repositório independente: https://github.com/dabaphira/litoral-arretado

## Executar
`python3 -m http.server 8765` nesta pasta. Sem dependências, build ou mensalidade de aplicação. Publicar todos os arquivos HTML, WebP e JPG juntos.

## Hospedagem
Infraestrutura verificada em 24/10/2026: domínio servido por Cloudflare; repositório felipedesordeiro/dabaphira contém o site principal e a pasta erivan-passeios. Esta implementação adiciona somente litoral-arretado/, sem alterar arquivos preexistentes, DNS ou configuração global. O repositório independente conserva o código e a documentação; os arquivos públicos são espelhados na pasta do site principal para publicação. Não existe sincronização automática entre ambos. Atualizações futuras devem publicar nos dois locais.

## Conteúdo
Logo original fornecida pelo usuário. Fotos do Instagram reutilizadas com autorização expressamente confirmada nesta conversa. SOURCES.md documenta imagens e avaliações. Não foram inventados preços, duração, inclusões ou políticas. As fotos dos cards buggy e Crôa são paisagens representativas do acervo; não comprovam localização específica ou veículo.

## Recursos
WhatsApp +5582988163949 com mensagens por serviço. Formulário monta mensagem com experiência, data e pessoas; nada é enviado antes de confirmação no WhatsApp. Sem coleta ou armazenamento pelo site. Ícone original reutilizado do site Dabaphira. SEO local com TravelAgency, canonical e OpenGraph. Sem aggregateRating para depoimentos da própria empresa. Avaliações são recorte manual datado, sem sincronização automática. Galeria CSS com pausa e prefers-reduced-motion; imagens WebP locais, fontes do sistema, lazy loading e prioridade na foto principal.

## Rastreamento opcional
Desativado. É possível conectar futuramente Cloudflare Web Analytics gratuito pelo painel da hospedagem, usando o identificador real da conta. Nenhum pixel, cookie de marketing, ID fictício ou serviço pago foi instalado.

## Validação
Conferir 320, 390, 768 e desktop; ausência de rolagem horizontal; imagens carregadas; menu, FAQ, pausa e links por experiência. Mensagens são verificadas pelos URLs gerados, sem enviar mensagens à empresa. A prova definitiva de publicação é o conteúdo retornado no domínio, e não apenas um commit ou HTTP 200 (a hospedagem retornava o site principal para esta rota inexistente).
