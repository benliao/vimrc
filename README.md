# A vimrc file for coding rust lang in vim
# Step
- Download vim-plug
```shell
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
``` 
- Clone this repository.
- Copy vimrc to ~/.vimrc
- start vim, ignore erros and run :PlugInstall
# For ruster
- Install rls in bash
```bash
rustup component add rls rust-analysis rust-src
```
- Then in vim run
```
:CocInstall coc-rls
```
- Install racer
```
rustup toolchain add nightly
cargo +nightly install racer

```
- coc rust analyzer
```bash
:CocInstall coc-rust-analyzer
```
- Restart vim and choos Y when prompted to install rust analyzer.
