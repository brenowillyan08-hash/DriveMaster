# DriveMaster

Protótipo "Real Car" usando Three.js + Ammo.js (WASM). Implementação simples com aproximação do carro por caixa (box-approx).

Descrição
- Visual: Three.js
- Física: Ammo.js (WASM)
- Controles: W/A/S/D ou setas, Espaço = freio de mão, R = reiniciar

Como rodar (local)
1. Clone/crie o repositório no GitHub (veja comandos abaixo).
2. Sirva a pasta por um servidor local (o import dinâmico do WASM precisa de servidor, não funciona abrindo arquivo diretamente):
   - Python 3: `python -m http.server 8000`
   - Node: `npx serve .`
3. Abra no navegador: `http://localhost:8000`

Como testar
- Clique em "Iniciar Protótipo" no menu.
- Aguarde o carregamento do Ammo (WASM).
- Use os controles para dirigir.

Observações
- Recomendado para desktop (mouse + teclado).
- Se houver problemas com o CDN do Ammo, verifique a URL em `main.js` e substitua por uma versão compatível.

Licença
- MIT (veja o arquivo LICENSE)

Autor
- brenowillyan08-hash