## My Emacs Configurations
### For Rust
Make sure to install rust-analyser
```
$ git clone https://github.com/rust-analyzer/rust-analyzer.git
$ cd rust-analyser
$ cargo xtask install --server # will install rust-analyzer into $HOME/.cargo/bin
```

### For Javascript and LSP
```
$ sudo npm install -g typescript-language-server
$ sudo npm install -g typescript
```

### For Python and LSP
```
$ pip install 'python-lsp-server[all]'
```

### For Go
Install golang and gopls. Following command is for fedora
```
$ sudo dnf install golang golang-x-tools-gopls
```

#### Following Packages may not be necessary
```
$ sudo npm install -g prettier
$ sudo npm install -g eslint
```
