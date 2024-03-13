Installing on windows:
install packer manager in windows powershell
git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"

copy files into Appdata/local/nvim
run nvim, open packer.lua in nvim, :so then :PackerSync
download gcc if not install recommend choco install mingw
relaunch nvim should download treesitter
modify lsp.lua and treesitter, might have some that dont work on windows
