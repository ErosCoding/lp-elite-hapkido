# Elite Hapkido — Landing page

Site estático (um `index.html` + pasta `assets/`). Sem build: a Vercel serve direto.

## Editar contato, endereço e horários
No topo do `<script>` em `index.html`, objeto `CONFIG`:

- `whatsapp`: número só com dígitos (ex.: `553193313678`). Vazio = botões vão para o direct do Instagram.
- `instagram` / `instagramDM`: links do perfil.
- `address`: endereço usado no botão do Google Maps.
- `schedule`: horários das aulas (vazio mostra "horários sob consulta").

## Fotos e vídeos
Ficam em `assets/` (webp para fotos; mp4 H.264 + poster webp para vídeos). Para trocar, substitua o arquivo mantendo o mesmo nome.

## Deploy
Cada push na `main` publica na Vercel automaticamente.
