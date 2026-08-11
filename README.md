# 🎓 UFERSAMV-RPG

> Uma solução de tecnologia educacional focada em gamificação, desenvolvida para integrar o ecossistema de aprendizado do semiárido. O projeto atua como o ambiente digital da iniciativa de *Escape Room* da incubadora Ineagro, promovendo o engajamento estudantil através de experiências híbridas.
> 
> 📄 **Propriedade Intelectual:** Software registrado no INPI (Processo BR512026000128-5).

---

## 🛠️ Tecnologias e Pré-requisitos

Para executar e contribuir com o projeto, é necessário o seguinte ambiente de desenvolvimento:

*   **Engine:** [RPG Maker MV](https://store.steampowered.com/sub/88038/) (Requer licença ativa via Steam).
*   **Versionamento:** Git / [GitHub Desktop](https://desktop.github.com/).

---

## 🚀 Instalação e Configuração (Setup)

1. **Clonando o Repositório:**
   * Abra o GitHub Desktop.
   * Navegue até `File > Clone Repository...`
   * Localize o repositório `UFERSAMV-RPG` e defina o diretório local (ex: `Documentos/Games/UFERSAMV-RPG`).
   * Clique em **Clone** e aguarde a finalização do download.

2. **Inicializando o Projeto:**
   * Navegue até o diretório local clonado.
   * Execute o arquivo `Game.rpgproject`.
   * O RPG Maker MV será inicializado com a versão mais recente (HEAD) da branch atual.

---

## 🔄 Fluxo de Contribuição (Workflow)

Para garantirmos a integridade do código e dos assets do jogo, todo o time deve operar sob a seguinte regra de ouro: **Sempre sincronize a base de código antes de iniciar o desenvolvimento.**

### O Ciclo Diário de Desenvolvimento

1. **Pull (Sincronização):** No GitHub Desktop, clique em `Fetch origin` (ou `Pull origin` se houver alterações pendentes). Isso garante que você está trabalhando na versão mais atualizada.
2. **Work (Desenvolvimento):** Abra o projeto, crie seus mapas, programe os eventos e salve as alterações no editor.
3. **Commit (Registro):** Retorne ao GitHub Desktop. Revise os arquivos alterados e crie um commit semântico (veja os padrões abaixo).
4. **Push (Envio):** Clique em `Push origin` para enviar suas atualizações para o repositório remoto.

> **Resumo do Ciclo:** `Pull` ➔ `Work` ➔ `Commit` ➔ `Push`

---

## 📝 Padrões de Commit (Conventional Commits)

Para manter o histórico legível e profissional, recomendamos o uso de prefixos no título das suas mensagens de commit:

*   `feat:` Para novas funcionalidades (ex: *feat: cria o NPC da biblioteca e estrutura de diálogos*).
*   `fix:` Para correção de bugs (ex: *fix: corrige colisão no mapa do laboratório*).
*   `docs:` Para alterações na documentação ou README.
*   `assets:` Para adição ou modificação de imagens, áudios e sprites.
