# Notetaker — instaladores

Transcrição de reuniões que roda **no seu computador**. O áudio não sai da máquina.

Este repositório não tem código: ele existe só para hospedar as releases, que é de
onde o app se atualiza. O código é privado.

## Baixar

Os instaladores estão na [página de releases](../../releases/latest).

| Sistema | Arquivo |
|---|---|
| Windows | `NotetakerSetup-x.y.z.exe` |
| macOS (Apple Silicon) | `Notetaker-x.y.z-arm64.dmg` |

## Nenhum dos dois é assinado ainda

**Windows.** O SmartScreen avisa que o editor é desconhecido. *Mais informações* →
*Executar assim mesmo*.

**macOS.** O primeiro abrir é bloqueado com "não foi possível verificar". O caminho é
Ajustes do Sistema → Privacidade e Segurança → rolar até o aviso → *Abrir Mesmo Assim*.

## Atualizações

No Windows o app se atualiza sozinho: baixa em segundo plano e instala quando você
fecha. No macOS ele avisa que há versão nova e manda você baixar o `.dmg` daqui —
atualizar sozinho exige assinatura, que ainda não existe.
