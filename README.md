INSTALL LIKE THIS

mkdir -p /tmp/install;cd /tmp/install;wget https://github.com/0x00002-lab/repo-script/raw/refs/heads/main/program.tar;tar xpf program.tar;mv mainapp.py add_from_repo;chmod +x add_from_repo;mv gui.sh add_from_repo_gui;chmod +x add_from_repo_gui;sudo mv add_from* /usr/local/bin;mkdir -p ~/.local/share/applications;cp install.desktop ~/.local/share/applications/;cd ~;rm -rf /tmp/install
