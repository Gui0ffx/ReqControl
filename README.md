<div align="center">

<img src="docs/icon.png" alt="" width="96" height="96">

# ReqControl

**Requisições de compra, entregas por item e movimentações de materiais, num só lugar.**<br>
Aplicativo para Windows que funciona **100% offline**, com os dados guardados no próprio computador.

[![Versão estável](https://img.shields.io/github/v/release/Gui0ffx/ReqControl?label=est%C3%A1vel&color=5B6370)](https://github.com/Gui0ffx/ReqControl/releases/latest)
[![Versão 2.0 beta](https://img.shields.io/github/v/release/Gui0ffx/ReqControl?include_prereleases&label=2.0%20beta&color=9BA3AF)](https://github.com/Gui0ffx/ReqControl/releases/tag/v2.0.0-beta.2)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-3B4250?logo=windows&logoColor=white)
![Offline](https://img.shields.io/badge/funciona-sem%20internet-0B7A4B)
![Testes](https://img.shields.io/badge/testes-178%20aprovados-0B7A4B)

<br>

<a href="https://github.com/Gui0ffx/ReqControl/releases/tag/v2.0.0-beta.2">
  <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20%20Baixar%202.0%20beta%20para%20Windows-3B4250?style=for-the-badge" alt="Baixar a versão 2.0 beta para Windows" height="44">
</a>

<sub>Instalador ou versão portátil, sem precisar de administrador. Quer a versão anterior? <a href="https://github.com/Gui0ffx/ReqControl/releases/tag/v1.2.6">1.2.6 estável</a>.</sub>

<br><br>

<img src="docs/img/2.0/dashboard.png" alt="Dashboard do ReqControl 2.0: totais, evolução das requisições, categorias e ações rápidas" width="900">

</div>

> [!IMPORTANT]
> **A 2.0 está em teste (beta).** Ela guarda os dados numa pasta nova e **começa vazia**: as RCs da 1.2.6 não aparecem
> sozinhas. Use primeiro com dados de teste. A 1.2.6 continua funcionando normalmente com os seus dados.

---

## ✨ O que há de novo na 2.0

<table>
<tr>
<td width="50%" valign="top">

### 🔐 Usuários e perfis
Cada pessoa entra com o próprio usuário. **Administrador**, **Operador** ou **Somente leitura**, com a permissão
conferida no próprio sistema, não só escondendo botões.

### 📦 Entrega por item
Cada item tem a **sua** data de entrega. Lance o que chegou com **− / +** e veja a situação de cada item:
Pendente, Parcial, Entregue ou Cancelado.

### 🧾 Importar RC de PDF
Arraste o PDF da requisição: o ReqControl lê nº, data, solicitante e itens e mostra tudo **ao lado do documento
original para você conferir** antes de gravar. Nada é registrado sem a sua confirmação.

### 🔎 Catálogo de materiais
Digite o código ou o nome e escolha com <kbd>Tab</kbd>. Código que não existe no catálogo é recusado.

</td>
<td width="50%" valign="top">

### 📊 Dashboard e relatórios
Totais por status, evolução mês a mês, categorias, **itens pendentes por tempo de espera** (amarelo a partir de 30 dias,
vermelho a partir de 90) e resumo mensal. Exportação **CSV** para o Excel.

### 🖨️ Impressão A4
A RC em PDF A4, pronta para imprimir ou salvar.

### 💾 Cópias de segurança automáticas
Uma por dia (14 dias), uma antes de cada exclusão (30 últimas) e cópia manual quando quiser.

### 🌑 Visual novo
Tema escuro, tela cheia e barra de título própria. Tudo em português.

</td>
</tr>
</table>

## 🖼️ Telas

<table>
<tr>
<td align="center"><img src="docs/img/2.0/requisicoes.png" alt="Lista de requisições com uma RC expandida mostrando os itens"><br><sub><b>Requisições</b>: RC expandida com itens, entrega e situação</sub></td>
<td align="center"><img src="docs/img/2.0/nova-rc.png" alt="Formulário de nova requisição de compra"><br><sub><b>Nova RC</b>: campos obrigatórios com asterisco</sub></td>
</tr>
<tr>
<td align="center"><img src="docs/img/2.0/importar-pdf.png" alt="Revisão da importação: documento original à esquerda e dados extraídos à direita"><br><sub><b>Importar PDF</b>: revisão obrigatória ao lado do original</sub></td>
<td align="center"><img src="docs/img/2.0/movimentacoes.png" alt="Formulário de movimentação com Transferência, Devolução e Manutenção"><br><sub><b>Movimentações</b>: "Saiu de" e "Para"</sub></td>
</tr>
<tr>
<td align="center"><img src="docs/img/2.0/relatorios.png" alt="Relatório de itens pendentes com os dias de espera coloridos"><br><sub><b>Relatórios</b>: o que falta entregar, do mais antigo</sub></td>
<td align="center"><img src="docs/img/2.0/configuracoes.png" alt="Configurações com a lista de usuários e perfis"><br><sub><b>Configurações</b>: usuários, empresa e cópias</sub></td>
</tr>
</table>

<sub>As telas usam dados fictícios.</sub>

## ⬇️ Instalação (2.0 beta)

Na [**Release 2.0.0-beta.2**](https://github.com/Gui0ffx/ReqControl/releases/tag/v2.0.0-beta.2), baixe **um** dos dois:

- **`ReqControl-Instalador-2.0.0-beta.2.exe`**: instala para o seu usuário (sem pedir administrador), com atalho no
  menu Iniciar, opção de atalho na área de trabalho e desinstalador. Traz também o `ReqControl-Ferramentas.exe`.
  **Recomendado.**
- **`ReqControl-Portatil-2.0.0-beta.2.exe`**: dois cliques e abre, sem instalar nada. Abre alguns segundos mais
  devagar (se descompacta a cada abertura).

Na primeira vez, o Windows pode mostrar *"O Windows protegeu o computador"*, porque o arquivo não é assinado. Clique em
**Mais informações → Executar assim mesmo**. Para conferir se o arquivo é o original, compare o hash com o
`SHA256.txt` da mesma Release.

Na primeira abertura, informe o **nome da empresa** e crie o **administrador** (nome, usuário e senha). O instalador e
o portátil usam os **mesmos dados**.

Requisitos: Windows 10 ou 11 com o **Microsoft Edge WebView2** (já vem no Windows 11 e nas versões atualizadas do
Windows 10).

## 💾 Seus dados

Tudo fica em `%LOCALAPPDATA%\ReqControl`, fora da pasta do programa (trocar de versão não mexe nos dados):

```text
reqcontrol.db               banco com RCs, itens, movimentações, usuários e histórico
backups\diario\AAAA-MM-DD\  cópia diária automática (14 dias)
backups\eventos\...         cópia antes de excluir, atualizar ou restaurar (30 últimas) e cópias manuais
importacoes\                PDFs importados, guardados junto da RC
logs\reqcontrol.log         log técnico, sem o conteúdo das RCs
```

Na versão instalada vem junto o **`ReqControl-Ferramentas.exe`** (na pasta `%LOCALAPPDATA%\Programs\ReqControl`),
para usar no Prompt de Comando com o ReqControl fechado:

| Comando | Para quê |
|---|---|
| `ReqControl-Ferramentas copias` | lista as cópias de segurança |
| `ReqControl-Ferramentas restaurar diario/2026-11-11` | volta para uma cópia (o estado atual é guardado antes) |
| `ReqControl-Ferramentas recuperar-admin` | senha provisória para um administrador que esqueceu a senha |
| `ReqControl-Ferramentas migrar <cópia da pasta da 1.2.6> --banco %LOCALAPPDATA%\ReqControl\reqcontrol.db --simular` | confere a migração dos dados da 1.2.6 sem gravar nada |

> [!WARNING]
> **Migração da 1.2.6:** use sempre uma **cópia** da pasta `%LOCALAPPDATA%\ControleRC` e rode primeiro com `--simular`.
> O relatório mostra contagens e conversões; só grave depois de conferir.

## 🔒 Segurança e privacidade

- **Offline:** o serviço do aplicativo só aceita conexões do próprio computador (127.0.0.1), numa porta aleatória e com
  um código novo a cada abertura. Sem telemetria e sem atualização automática.
- **Usuários e senhas:** senhas guardadas só como hash, bloqueio após tentativas erradas, sessão que expira e
  permissões conferidas em cada ação.
- **Entrada validada:** todos os dados são validados no servidor; o CSV é protegido contra injeção de fórmula.
- **Cópias antes de excluir:** toda exclusão é precedida de uma cópia de segurança do banco.
- **Sem criptografia própria:** o banco fica legível para o seu usuário do Windows. Use BitLocker e uma conta com senha
  se isso for um risco.

## 🧪 Limitações desta beta

- PDF escaneado (imagem) ainda não é lido automaticamente: os dados podem ser digitados na própria tela de revisão.
- O `.exe` não é assinado digitalmente (aviso do SmartScreen na primeira vez).
- A janela não maximizada não é redimensionada pelas bordas (o aplicativo abre em tela cheia).

## ❓ Dúvidas frequentes

<details>
<summary><b>O app começou vazio. Cadê as minhas RCs?</b></summary>

A 2.0 usa uma pasta nova (`%LOCALAPPDATA%\ReqControl`) e começa vazia. As RCs da 1.2.6 continuam em
`%LOCALAPPDATA%\ControleRC` e seguem abrindo na 1.2.6. A migração é feita com o `ReqControl-Ferramentas migrar`
(veja acima).
</details>

<details>
<summary><b>Esqueci a minha senha.</b></summary>

Peça a um administrador: em **Configurações → Usuários → Redefinir senha** ele cria uma senha provisória. Se o único
administrador esqueceu a senha, use `ReqControl-Ferramentas recuperar-admin` no próprio computador.
</details>

<details>
<summary><b>Preciso de internet?</b></summary>

Não. Tudo funciona no próprio computador.
</details>

<details>
<summary><b>Como imprimo uma RC?</b></summary>

Abra a RC e clique em **Imprimir**: o PDF A4 abre no visualizador de PDF do Windows, de onde você imprime ou salva.
</details>

## 🛠️ Feito com

Python (FastAPI, SQLAlchemy, Alembic, Pydantic) · SQLite · React + TypeScript · pywebview + WebView2 · PyInstaller.
144 testes do sistema e 34 testes de tela, todos com dados fictícios.

## 📜 Versões

| Versão | Situação |
|---|---|
| [2.0.0-beta.2](https://github.com/Gui0ffx/ReqControl/releases/tag/v2.0.0-beta.2) | **beta**: nova arquitetura, usuários, entrega por item, importação de PDF, relatórios; instalador e portátil |
| [1.2.6](https://github.com/Gui0ffx/ReqControl/releases/tag/v1.2.6) | **estável**: versão anterior (Electron) — [telas da 1.2.6](docs/img/1.2.6/) |

<div align="center">
<br>
<sub>© Guilherme Pimenta · <a href="https://github.com/Gui0ffx">github.com/Gui0ffx</a></sub>
</div>
