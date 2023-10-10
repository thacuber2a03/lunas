# lunas
an Uxntal assembler written in Lua

### how to use
download or clone this repository, then
- in Linux or MacOS (possibly), just run the `lunas` file like a program
  ```sh
  ./lunas myapp.tal myapp.rom
  ```
- in Windows, there's no support for shebangs, so you have to directly run the Lua interpreter over said file
  ```bat
  lua .\lunas myapp.tal myapp.rom
  ```

### dependencies
there are no other dependencies apart from needing a Lua 5.4 interpreter, the file is totally self contained

### features
- better error reporting and warnings
- easily modifiable and extendable (possibly (I have not tried this))

### checklist
- [x] comments
- [x] `[`, `]`, `{` and `}` 
- [x] basic opcode assembling
- [x] literal runes
- [x] padding runes
- [x] labels
- [x] raw numbers
- [x] addressing runes
- [x] ascii rune
- [x] macros
- [ ] relative addressing runes
- [ ] jumping runes
- [ ] preprocessor runes

