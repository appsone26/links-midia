# Selo "Oferta verificada" — Cataki

Selo oficial para posts, capas, vídeos e propaganda. PNG com fundo transparente (recortado de verdade).

| Arquivo | Quando usar |
|---|---|
| `selo-1024.png` | Peça grande: post sobre o selo, propaganda, capa de vídeo |
| `selo-512.png` | Canto de card ou capa de carrossel |
| `selo-256.png` | Selo médio em card de oferta |
| `selo-128.png` | Selinho ao lado de texto |
| `selo-64.png` | Miniatura mínima (acima disso o texto fica ilegível) |
| `selo-1024-giro-12.png`, `selo-1024-giro+12.png`, `selo-1024-giro-25.png` | Selo inclinado, estilo carimbo; reduzir com Pillow conforme o uso |

Para outro ângulo: girar o `selo-1024.png` com `Image.rotate(ang, expand=True, resample=Image.BICUBIC)` e reduzir só no final.

Observação: a versão original tinha "CATAKI" duas vezes; foi removido o de baixo (20/10/2026).
