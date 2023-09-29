# bum

<img src="https://github.com/owenizedd/bum/assets/26961166/b231b1ff-dcde-4cc1-a0de-fa0f4964e54e" height="auto" width="150" style="border-radius:50%">
<br/>     

<a href="https://github.com/owenizedd/bum/actions/workflows/rust.yml"><img alt="GitHub CI Status" src="https://img.shields.io/github/actions/workflow/status/owenizedd/bum/rust.yml?label=CI&logo=GitHub"></a> <br/>
## Bum - Bun Version Manager   

Introducing Bum, a Bun version manager.  
Built in Rust from scratch.
There are many future improvements, but I can say it's really fast to use!

Bum initial version is released! You can see the [releases page](https://github.com/owenizedd/bum/releases)

## To install:
- `curl -fsSL https://github.com/owenizedd/bum/raw/main/install.sh | bash`
  > This installation will install bun for you and also bum altogether.  
  > Bum is supported on Linux x86_64 and Darwin x86_64 (Mac OS)
- Restart terminal or `source ~/.zshrc` or `source ~/.bashrc` depending on your terminal.


## How to use:
- You can just run `bum` without any parameter to see default menu.

```yaml
      _____    ___   ____      _____  _______        
      ___|\       |    | |    |   |      \/       \  
     |    |\    \ |    | |    |  /          /\     \ 
     |    | |    ||    | |    | /     /\   / /\     |
     |    | /_ _/ |    | |    |      /\ \_/ / /    /|
     |    |\      |    | |    ||    |  \|_|/ /    / |
     |    | |   | |    | |    ||    |       |    |  |
     |____|/____| |\___\_|____||____\       |____|  /
     |    /     | | |    |    |||    |      |    | / 
     |____|_____/  \|____|____| |____|      |____|/  
       \(    )/       \(   )/     \(          )/     
        '    '         '   '       '          '       
Usage: bum <COMMAND>

Commands:
  default  
  use      
  remove   
  help     Print this message or the help of the given subcommand(s)

Options:
  -h, --help  Print help
```

- Or directly use: `bum use <version>`
   - e.g. `bum use 1.0.3`
   - This will automatically use v1.0.3, yes no need write suffix `v`.
   - If there's no target version is installed in the local, it will install that version then use it.
   - Else, it will just use that version as active version.

Any contribution is appreciated.
