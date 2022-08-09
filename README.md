AstroNvim

This is settings for AstroNvim.

Instalation:

1) Install <a href="https://github.com/AstroNvim/AstroNvim"> AstroNvim </a>

2) Clone this repo in ~/.config/nvim/lua/user:
	
		git clone https://github.com/sgkochnev/astronvim_config.git ~/.config/nvim/lua/user

3) Initlialize AstroNvim:
	
		nvim --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'
