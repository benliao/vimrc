# Step
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
```
:CocInstall coc-rust-analyzer
```

