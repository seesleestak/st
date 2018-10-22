# Custom st build

`st` built with the following patches applied:  
- [scrollback](https://st.suckless.org/patches/scrollback/) (Including mouse scrollback)  
- [copyurl](https://st.suckless.org/patches/copyurl/)  

I've also added some of my preferred defaults to the `config.def.h`:  
- [Nord](https://github.com/arcticicestudio/nord/issues/89) colorscheme  
- DejaVu Sans Mono
- 8px internal border

## Installing

```
git clone https://github.com/seesleestak/st.git && cd st
make && sudo make install
```
