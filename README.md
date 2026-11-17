
# MineKB 360

Projeto experimental para utilizar mouse e teclado USB no Minecraft: Xbox 360 Edition.

## Objetivo

Criar uma solução para Xbox 360 RGH/JTAG que converta entradas de teclado e mouse em comandos compatíveis com o controle do console.

## Controles planejados

| Tecla ou botão | Ação |
|---|---|
| W, A, S, D | Movimentação |
| Mouse | Câmera |
| Espaço | Pular |
| Shift | Agachar |
| Botão esquerdo | Quebrar blocos |
| Botão direito | Colocar blocos |
| E | Inventário |
| Esc | Pausar |

## Arquitetura

- Plugin de sistema para receber entradas USB.
- Camada de conversão de teclado e mouse.
- Mapeamento para comandos de controle.
- Perfis de configuração.
- Testes de compatibilidade com Minecraft.

## Referência técnica

X360Remap: projeto público de mouse e teclado para Xbox 360.

https://github.com/HB-Agadir/x360remap

O X360Remap utiliza licença GPL-3.0. Qualquer código derivado deverá respeitar essa licença e seus avisos de autoria.

## Estado do projeto

- [x] Repositório criado.
- [x] Arquitetura inicial definida.
- [ ] Leitura USB HID validada.
- [ ] Conversão de teclado validada.
- [ ] Conversão de mouse validada.
- [ ] Compatibilidade com Minecraft testada.
- [ ] Compilação final do plugin.

**Status:** Em desenvolvimento.
