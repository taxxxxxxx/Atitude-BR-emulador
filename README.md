# Atitude-BR-emulador🇧🇷# ⚡ ATITUDE BR ⚡
### Sistema Windows para Celulares Android | GPU Mali

🇧🇷 Projeto brasileiro desenvolvido para rodar programas e jogos Windows diretamente em celulares com processador ARM e GPU Mali, sem precisar de Snapdragon.

---

## ✅ CARACTERÍSTICAS
- 🚀 **Leve e Rápido**: Baseado em Wine 9.x otimizado.
- 📂 **Discos Prontos**:
  - 💽 **Disco C:** → Sistema
  - 💾 **Disco D:** → Arquivos e Jogos (Ligado na pasta Download)
  - 📁 **Z:** → Acesso total ao celular
- 🔊 **Áudio Funcionando**
- 🎨 **Personalizável**
- ❌ **Sem complicação**: Apertou, rodou!

---

## 📲 COMO INSTALAR

1.  Instale o **Termux** e o **Termux-X11** no seu celular.
2.  Abra o Termux e digite:
    ```bash
    pkg update && pkg upgrade -y
    pkg install wget -y
    ```
3.  Baixe o instalador:
    ```bash
    wget https://raw.githubusercontent.com/SEU-NOME/ATITUDE-BR/main/install
    chmod +x install
    ./install
    ```
4.  Pronto! Para iniciar sempre digite:
    ```bash
    atitude
    ```
#!/data/data/com.termux/files/usr/bin/bash
# =========================================
# ⚡ INSTALADOR OFICIAL - ATITUDE BR
# =========================================

clear
echo " █████╗ ██╗████████╗███████╗██████╗ "
echo "██╔══██╗██║╚══██╔══╝██╔════╝██╔══██╗ "
echo "███████║██║   ██║   █████╗  ██████╔╝ "
echo "██╔══██║██║   ██║   ██╔══╝  ██╔══██╗ "
echo "██║  ██║██║   ██║   ███████╗██║  ██║ "
echo "╚═╝  ╚═╝╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═╝ "
echo "                                         "
echo "          🇧🇷 INICIANDO INSTALAÇÃO 🇧🇷    "

pkg update -y
pkg install -y x11-repo pulseaudio wget termux-x11-nightly

echo "📥 Baixando sistema base..."
# Aqui vai o comando de baixar o glibc e wine
# (Você já sabe o código que deu certo)

echo "🔧 Criando comando principal..."
# (Aqui ele copia o arquivo 'atitude' para a pasta bin)

echo ""
echo "✅ INSTALAÇÃO CONCLUÍDA!"
echo "🚀 DIGITE: atitude"
echo ""

---

## 🎨 COMO COLOCAR PAPEL DE PAREDE
Dentro do sistema, navegue até `C:\opt\` e execute o arquivo `atitude_parede.bat`.

---

## 🛠️ REQUISITOS
- Android 10 ou superior
- Pelo menos 4GB de RAM
- GPU Mali (funciona em celulares da Samsung, Motorola, etc)

---

### 🇧🇷 DESENVOLVIDO POR:
**SEU NOME / EQUIPE ATITUDE BR**
> *Não é só emular, é ter Atitude!*
> 
