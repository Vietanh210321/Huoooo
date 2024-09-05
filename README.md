function install () {
  clear; curl -L --max-redirs 15 --progress-bar "https://github.com/Vietanh210321/Ninja_Server_Termux/script_install.sh" --output script_install.sh && bash script_install.sh || echo "Internet ERROR"; unset install
}
install
